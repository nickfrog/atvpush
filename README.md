# HomeAssistant .yaml file content for image push notifications on Apple TV 

You want to receive HomeAssistant triggered notifications on your Apple TV whilst watching your facorite movie?

1. Use the code snippets out of the code.yaml file and distribute the snippets to the right *.yaml files
2. Upload your prebuilt images to your HomeAssistant "www" folder (and adjust the used images in the code snippets .../www/...)
3. Restart HomeAssistant
4. Add the new Homekit Bridge to Apple Home using the "Home" App
5. Turn on your Apple TV and check that you can receive notifications from the new "Camera" (Apple TV settings - Homekit - ...)
6. Trigger the "automation.homekit_notification_demo" - Automation and see what happens
7. Think about your notification use cases and create the images and notifications for them
8. Never miss important things whilst you are watching your favorite show

In my case it looks like this:

https://github.com/nickfrog/atvpush/assets/83492721/528285ef-4345-455b-b999-dbf3e08d13c5

Forked from / based on the great of work rikardronnkvist
