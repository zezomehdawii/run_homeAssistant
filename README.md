# run_homeAssistant

```docker run --init -d --restart=unless-stopped --name="home-assistant" -e "TZ=Europe/Sofia" -v /EMPTY_FOLDER_ON_YOUR_HOST:/config -p 8123:8123 homeassistant/home-assistant:latest```
