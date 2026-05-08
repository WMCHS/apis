Hello fellow Technology Coordinator!

This API works alongside the Student New Tab Portal extension on Chromebooks. Here's the default setup:

{
  "messageID": 1, <-- INCREMENT BY 1 PER NEW MESSAGE
  "refreshesDaily": true, <-- If true, then every 12 hours after dismissing, the message will pop up again. False means it only pops up once.
  "header": "Chromebook Return!",
  "body": "Please return your Chromebooks to the main office."
}
