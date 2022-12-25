# heroku-buildpack-ngrok

## Requirements
  * Ngrok api token

## Environment variables
  * NGROK_WRAPPER_SCRIPT_NAME (optional) - specifies a script that starts a ngrok service.

The following will only work if NGROK_WRAPPER_SCRIPT_NAME is unchanged:
  * NGROK_API_TOKEN (required) - a personal ngrok api token.
  * NGROK_OPTS (optional) - additional options for ngrok service.
  * NGROK_PORT (optional) - a port to tunnel to.
  * NGROK_GET_IP_SCRIPT_NAME (optional) - where to write a script which returns ngrok server ip.
