---
title: "A New MessageBox"
date: "2023-05-14T08:10:37-07:00"
tags:
- Homer Jones
- 2023
image: ABSShowMessage.png
---

Homer Jones created a new Message Dialog that solves problems with the standard Delphi 2007 ones--and even the latest ones. The two main problems are: 1) they can be hidden behind other windows, and 2) they don't appear centered on the application's main form, even when Position is set to `poMainFormCenter` (that seems to have been fixed in later Delphi versions, but the former is still an issue). When a dialog box is hidden, the app freezes; they are modal, but the user can't respond because it's hidden.

A third problem has to do with the message itself. The standard dialogs have no way to gracefully add emphasis to critical parts of the message. It's important that messages do more than report errors. They should be instructive. If a user error occurs, it's just smart programming to tell them how to avoid it in the future, or how to fix it, or where to find more information. If you do that, your phone rings less.

The new Message Dialog has the same syntax as the standard `MessageDlg`, but has more optional parameters for the enhanced features. Because the additional parameters are optional, the new message can be a direct replacement for the existing code. Instead of coding `MessageDlg(...)`, you simply add a prefix to the command like: `ABSMessageDlg(...)`. That's all you need for a simple, backward compatible replacement. However, adding one or more parameters can enhance the user experience greatly. They permit adding a Vista TaskDialog style title to the text which can be any color. A custom caption can be placed on the dialog's form. For additional emphasis, the message is in a `TRichText` object. You can do cool things like underline, bold, italic, and color important parts of the message. See the example screenshot above.

A demonstration of this new message dialog will include a code review, and instructions for creating a rich text message. Join us for pizza or salad and learn how to enhance your application messages.

**POST MEETING NOTE**: Homer has provided a copy of his source code for this demonstration, along with comments and a demo app. It was written in Delphi 2007 but should work with any newer version: [ABSMessageDialog.zip](/files/presentations/2023_NewMessageBox/ABSMessageDialog.zip)

## PRESENTER ##

**Homer Jones** sells insurance agency management software written in Delphi through his company [Agency Business Systems](http://agencybusys.com/). 
