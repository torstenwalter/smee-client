# smee docker image

> [smee](https://github.com/probot/smee) is a web application that receives
> payloads then sends them, via the EventSource API, to other clients.

As explained in a
[blogpost](https://jenkins.io/blog/2019/01/07/webhook-firewalls/) it can be used
to forward GitHub webhooks to Jenkins.

docker run -it smee:latest -p 8080 --path /github-webhook/
