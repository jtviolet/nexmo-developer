---
title: Send a Video Message
meta_title: Send a Video message with WhatsApp
---

# Send a Video Message

In this code snippet you learn how to send a video message through WhatsApp using the Messages API. For WhatsApp the maximum outbound media size is 64MB.

## Example

Ensure the following variables are set to your required values using any convenient method:

Key | Description
-- | --
`BASE_URL` | For production use the base URL is `https://api.nexmo.com/`. For sandbox testing the base URL is `https://messages-sandbox.nexmo.com/`.
`MESSAGES_API_URL` | For production use the Messages API endpoint is `https://api.nexmo.com/v0.1/messages`. For sandbox testing the Messages API endpoint is `https://messages-sandbox.nexmo.com/v0.1/messages`.
`WHATSAPP_NUMBER` | The WhatsApp number that has been allocated to you by Nexmo. For sandbox testing the number is `14157386170`.
`TO_NUMBER` | The WhatsApp number you are sending to.
`VIDEO_URL` | The link to the video to send. WhatsApp supports `.mp4` and `.3gpp`. Note, only `H.264` video codec and `AAC` audio codecs are supported.
`VIDEO_CAPTION` | The caption text for the video.

```code_snippets
source: '_examples/messages/whatsapp/send-video'
application:
  type: messages
  name: 'Send a video message'
```

## Try it out

When you run the code a video message is sent to the WhatsApp recipient.
