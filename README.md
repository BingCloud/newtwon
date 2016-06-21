## About newtwon
newtwon is my slack robot, you can talk to him when you are boring.   
## Usage
simply deploy it to anywhere with docker.

```
newton:
    image: registry.aliyuncs.com/ringtail/newtwon:latest
    restart: always
    environment:
        - debug=true
        - key=<TUNLING_API_KEY>
        - token=<SLACK_TOKEN>
```

or simply run with docker 

```
docker run -d -e key=<TUNLING_API_KEY> -e token=<SLACK_TOKEN>  -e debug=true --name newtwon registry.aliyuncs.com/ringtail/newtwon:latest
```

## Run in local 

```
key=<TUNLING_API_KEY>  token=<SLACK_TOKEN> node index.js
```

## links  
tuling Api: tuling123.com
