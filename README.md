# ngrok-install-debain
one key install ngrok on debian

## launch server on back ground: 
nohup /usr/local/ngrok/bin/ngrokd -domain="example.com" -httpAddr=":80" &

## launch client on back ground:
nohub ngrok -config="your_config_path/your_config.cfg" -subdomain=your_subdomain your_port &

base on: https://www.augcat.com/archives/93
