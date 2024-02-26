## Image Generation

Open WebUI now supports image generation through the AUTOMATIC1111 API. To set this up, follow these steps:

### Initial Setup

1. Ensure that you have AUTOMATIC1111 installed.
2. Launch the WebUI with additional flags to enable API access:
   ```
   ./webui.sh --api --listen
   ```
   For Docker installations, use the `--listen` flag to allow connections outside of localhost.

### Configuring Open WebUI

1. In Open WebUI, navigate to Settings > Images.
2. In the API URL field, enter the address where AUTOMATIC1111's API is accessible, following this format:
   ```
   http://<your_automatic1111_address>:7860
   ```
   If you're running a Docker installation of Open WebUI and AUTOMATIC1111 on the same host, replace `<your_automatic1111_address>` with `host.docker.internal`.

Please note that, as of now, only the AUTOMATIC1111 API is supported for image generation within Open WebUI.