---
title: chat-ui
emoji: 🔥
colorFrom: purple
colorTo: purple
sdk: docker
pinned: false
license: apache-2.0
base_path: /chat
app_port: :3000  prod
app_dev_port: :5173 dev
---

# Cloudrack AI | Based On HF Chat UI
## [View The LIVE DEMO @ ai.cloudrack.ca | `Web Search Has Been Disabled For Demo`](https://ai.cloudrack.ca)
![Chat UI repository thumbnail](https://cdn.discordapp.com/attachments/1154471481145827470/1156766456709652520/chatui-websearch.png?ex=65162a36&is=6514d8b6&hm=011eb493d715884234c98391423b9c97a9c9704826a0ab69c697fdb102918f12&)
- [Donate by being social on my Discord - or by going to our donatebot link](https://donatebot.io/checkout/1154471425663574039?buyer=142025929454125056)
  
A chat interface using open source models, e.g. OpenAssistant or Llama. It is a SvelteKit app + a docker buildable image and it powers the [HuggingChat app on hf.co/chat](https://huggingface.co/chat).

# What Powers This AI Currently.
As this is a side project and i own a dell poweredge r210 server chasis rack mountable 1u server i wanted to test the minimal aspects of the ability of this chat ai.
- Powered on a dell r210 with cloudflared uses npm run dev | enable --host on dev package.json use pm2 start npm -- run dev too keep it alive then use cloudflared or zerotrust on CF to push ports if no port forwarding.
- Run by using docker for free utilizing our api key please note our master key is reset on our end and this is a cached version with no write access to [HF](https://huggingface.co)

  ```shell
  docker run -p 5173:5173 shoppmonster/cloudrack-ai:latest
  ```
 - To develop and run your own ChatUI please check out [`huggingface/chat-ui`](https://github.com/huggingface/chat-ui)
---
# Credits & Resources
- [Cloudrack.ca](https://cloudrack.ca/)
- [Cloudrack.ca AI](https://ai.cloudrack.ca/)
- [HuggingFace](https://huggingface.co/)
- [Serper.dev](https://serper.dev/)
- [AltasDB](https://www.mongodb.com/)
