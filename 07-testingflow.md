## Testing the Flow

To publish your flow:

1. Click on **MAKE LIVE**, and select your WhatsApp application.

1. To trigger it, send the keyword: `instantconnect`

   The customer interaction you should get is shown below::

   ![WhatsApp1](images/whatsapp1.png)]

1. Check that:

   * Your customer name (`Lab Customer` in the example) is used in the first answer.
   * The Guest meetings link is sent to the customer (refer to the image above).
   * The Expert receives a Webex message from the bot, including the meeting link:

   ![Webex Bot Message](images/webex_bot_message.png)

   * The mockAPI.io record is updated, with `vdeoCallScheduled: true`

   ![Mockio Record Updated](images/mockio_record_updated.png)

1. Join the meeting as the customer on your mobile device, and as the expert on your desktop device. 

   Try some of the Webex Instant Connect features, such as:

   * Video call control (mute/unmute, turn your video on/off, ..). 

   * Meeting end: guest can leave the meeting at any time, host can leave without ending, or end meeting for all

   * Change the video Layout

   * Share your screen

   * Blur your background

   * Remove background Noise

   * See the list of participants, and invite new guests

   * Chat

   * Integrate with Webex video endpoints, by configuring [Virtual Rounding](https://help.webex.com/en-us/article/6vsdoi/Configure-Virtual-Rounding). And with the possibility of [Controlling remote cameras](https://help.webex.com/en-us/article/nuwutmx/Control-remote-cameras-with-Instant-Connect)


For more information, visit [Webex Instant Connect @ Webex Help Center](https://help.webex.com/en-us/article/sv0h2ab/Webex-Instant-Connect).
