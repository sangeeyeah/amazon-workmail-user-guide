# Working with Email Messages<a name="email-messages"></a>

Send, copy, move, print, and delete email messages from Amazon WorkMail\. If your administrator has created an alias for you, you can also send email as an alias\.

**Topics**
+ [Sending Email Messages](#create_send_email)
+ [Sending Email from an Alias](#send_alias)
+ [Copying or Moving Email Messages](#copy_move_email)
+ [Printing Email Messages](#print_email)
+ [Deleting Email Messages](#delete_email_message)

## Sending Email Messages<a name="create_send_email"></a>

You can create and send a message to one or more recipients, include attachments, set the priority, or add a flag to indicate that the message is important\.

**To send a message**

1. In the Amazon WorkMail web application, choose the mail icon on the shortcut bar\.

1. On the menu bar, choose **\+ New item** and **New email**\.
**Tip**  
You can also choose the plus sign \(\+\) on the tab bar\.

1. To add recipients, for **To**, type one or more names\. Amazon WorkMail suggests previously used email addresses\. You can remove suggestions from this list by selecting a name and choosing **Delete**\.

   To add users from the address book or to add them to the **CC** or **BCC** fields, choose **To**, and select one or more users from the address book as appropriate\.

1. \(Optional\) Do one of the following:
   + To add an attachment, choose **Attach**\. For more information on attachments, see [Working with Attachments](email-attachments.md)\.
   + To mark the message as important or high priority, low priority, or for follow\-up, choose the exclamation mark \(\!\), down arrow, or flag icon\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/workmail/latest/userguide/images/follow-up-flags.png)
   + To mark the message for follow\-up or as a completed task, choose the flag or the checkmark icon\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/workmail/latest/userguide/images/email-flags.png)
   + To save the message as a draft in the **Drafts** folder, choose **Save**\.

1. Enter your text in the lower half of the contents pane, and choose **Send**\.

## Sending Email from an Alias<a name="send_alias"></a>

You can send and receive email using an alias that your administrator configures for you\. Recipients outside of your organization then see the sender as your alias address instead of your primary address\. For information about configuring aliases, see [Edit User Email Addresses](https://docs.aws.amazon.com/workmail/latest/adminguide/edit_user_email_addresses.html)\.

**Note**  
If you send an email from an alias to someone in your organization, the message is still received from your primary address\. 

**To send an email from an alias**

1. In the Amazon WorkMail web application, choose the mail icon on the shortcut bar and choose **\+ New item**, **New email**\.

1. For **From**, type the alias from which to send email\.
**Tip**  
To include a display name, use the SMTP standard format `Your Name <youralias@domain.com>`\.

1. When you're ready to send the email, choose **Send**\.

**Note**  
 For information about sending email as a delegate, see [Working with Delegates](delegates_overview.md)\. 

## Copying or Moving Email Messages<a name="copy_move_email"></a>

You can copy or move a message from one folder to another\.

**To copy or move a message**

1. In the Amazon WorkMail web application, choose the mail icon on the shortcut bar\.

1. Do one of the following:
   + To copy an item, select the message in the contents pane and choose **Copy/Move**\.
   + To copy more than one message, press the **Ctrl** key while you select each message in the contents pane, and then choose **Copy/Move**\.
   + To move a single message, drag the item to its new location\.
**Tip**  
The folder names directly under the dragged message are highlighted and show the target location when you release the message\.
   + To move multiple consecutive messages, press the **Shift** key while you select all the messages to move, and then drag them to the desired folder\.
   + To move messages that are not consecutive, press the **Ctrl** key while you select each message to move, release the **Ctrl** key, and then drag them into the designated folder\.

1. In the **Copy/move messages** dialog box, select the destination folder and choose either **Copy** or **Move**\.

## Printing Email Messages<a name="print_email"></a>

If you have a printer attached to your computer and your computer is set up to print documents, you can print your messages\.

**To print a message**

1. In the Amazon WorkMail web application, on the shortcut bar, choose the mail icon\.

1. In the navigation pane, select the folder that contains the message to print\.

1. In the contents pane, select the message to print and choose **Print** on the menu bar\.

## Deleting Email Messages<a name="delete_email_message"></a>

When you no longer need an email message, you can delete it\. Deleting unwanted email also helps you to free up space in your inbox\.

**To delete a message**

1. In the Amazon WorkMail web application, choose the mail icon on the shortcut bar\.

1. Do one of the following:
   + In the contents pane, select a message and press the **Delete** key\.
   + In the contents pane, open the message and choose **Delete**\.
   + In the **Message** tab, choose **Delete**\.

If you mistakenly delete a message, calendar item, or contact, you can restore it\. All deleted email, calendar items, and contacts are stored in the Deleted Items folder in the application\.

**Note**  
You can only restore items that are still in the Deleted Items folder\. If you've emptied the Deleted Items folder, those items are unrecoverable\.

**To restore a deleted item**

1. In the Amazon WorkMail web application, choose the mail icon on the shortcut bar\.

1. In the **Deleted Items** folder, select the message to restore and choose **Copy/Move**\.
**Tip**  
You can also choose the plus sign \(\+\) on the tab bar\.

1. In the **Copy/move messages** dialog box, select the destination folder and choose **Move**\.