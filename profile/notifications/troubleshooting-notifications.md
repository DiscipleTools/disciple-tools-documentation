# Troubleshooting Notifications in Disciple.Tools

This guide helps you solve common problems with notifications in Disciple.Tools. Follow these steps to diagnose and fix notification issues.

## Common Notification Problems

### I'm Not Receiving Any Notifications

#### Check Your Notification Preferences
1. Go to your profile settings (click your **display name** on desktop or hamburger menu ☰ → **Settings** on mobile)
2. Scroll to the **Notifications** section
3. Verify that notification types are enabled for your preferred channels
4. Make sure at least **Web** notifications are enabled for testing

#### Verify Your Profile Information
1. Check that your **email address** is correct in your profile
2. Ensure your **phone number** is properly formatted (for SMS/WhatsApp)
3. Save any changes to your profile

#### Test with a Simple Mention
1. Ask a colleague to mention you in a comment: "@your-username test"
2. This should generate a notification within minutes
3. Check your notification bell icon and email

### I'm Not Receiving Email Notifications

#### Check Your Email Settings
1. Verify your **email address** is correct in your profile settings
2. Confirm email notifications are **enabled** for the types you want to receive
3. Check your **email delivery preference** (real-time, hourly, or daily digest)

#### Check Your Email Inbox
1. **Look in your spam/junk folder** - notification emails sometimes get filtered
2. **Add your Disciple.Tools site email** to your contacts to prevent spam filtering
3. **Check email rules** that might be automatically filing or deleting emails

#### Test Email Delivery
1. Change your email preference to **real-time** temporarily
2. Have someone **mention you** in a comment
3. You should receive an email within 5-10 minutes
4. If no email arrives, contact your system administrator

### I'm Not Receiving SMS or WhatsApp Notifications

#### Verify Channel Availability
1. Check if **SMS** or **WhatsApp** options appear in your notification settings
2. If these options are missing, your system administrator hasn't enabled them
3. Contact your administrator about enabling SMS/WhatsApp notifications

#### Check Your Phone Number
1. Verify your **phone number** is correctly entered in your profile
2. Use international format: +1234567890 (include country code)
3. **Remove spaces, dashes, or parentheses** from the phone number
4. Save your profile changes

#### Test SMS/WhatsApp Delivery
1. Enable SMS or WhatsApp for **mentions** only
2. Have someone mention you in a comment
3. You should receive a message within 5-10 minutes

### My Notification Count Seems Wrong

#### Clear Browser Cache
1. **Refresh your browser** (Ctrl+R or Cmd+R)
2. **Clear your browser cache** if the count still seems incorrect
3. **Log out and log back in** to reset your session

#### Mark Notifications as Read
1. Go to your **notifications page**
2. Click **Mark All as Read** to clear the count
3. The count should reset to show only new notifications

### I'm Receiving Too Many Notifications

#### Adjust Notification Preferences
1. **Disable email** for high-volume notification types like comments
2. **Switch to digest mode** for email notifications (hourly or daily)
3. **Keep only essential notifications** enabled for SMS/WhatsApp

#### Focus on Priority Notifications
1. **Keep assignments and mentions** enabled across all channels
2. **Disable comments** for email if you get too many
3. **Use web notifications** for less urgent updates

### I'm Receiving Duplicate Notifications

#### Understanding Multiple Channels
This is **normal behavior** - if you enable multiple channels for the same notification type, you'll receive the notification through each enabled channel. This ensures you don't miss important communications.

#### To Reduce Duplicates
1. **Choose one primary channel** per notification type
2. **Use SMS/WhatsApp** only for urgent notifications
3. **Use email** for records and less urgent updates
4. **Use web notifications** for regular workflow

## Specific Error Messages

### Error: "Notification preferences could not be saved"
**Cause**: Database or permission issue
**Solution**: 
1. Try refreshing the page and saving again
2. Check that you're still logged in
3. Contact your system administrator if the problem persists

### Error: "Email delivery failed"
**Cause**: Email server configuration issue
**Solution**:
1. This is a system-level problem
2. Contact your system administrator
3. Check your email address is correct in your profile

### Error: "SMS delivery failed"
**Cause**: SMS service configuration or phone number issue
**Solution**:
1. Verify your phone number format (+1234567890)
2. Check that SMS service is properly configured
3. Contact your system administrator

## Advanced Troubleshooting

### Check Browser Console for Errors
1. Open your browser's **developer tools** (F12)
2. Go to the **Console** tab
3. Look for red error messages when working with notifications
4. Share these errors with your system administrator

### Test Different Browsers
1. Try using notifications in a **different browser**
2. Test in **incognito/private mode**
3. This helps identify browser-specific issues

### Check Network Connectivity
1. Ensure you have a **stable internet connection**
2. Try accessing notifications from a **different network**
3. Check if your organization's firewall blocks notification features

## When to Contact Your System Administrator

Contact your administrator if:
- **No notification channels** are working despite correct settings
- **Email delivery fails** consistently
- **SMS/WhatsApp options** don't appear in settings
- **Error messages** appear when saving notification preferences
- **Multiple users** report the same notification problems

## Providing Information to Your Administrator

When reporting notification issues, include:
1. **Your username** and email address
2. **Specific notification types** that aren't working
3. **Which channels** you're having problems with
4. **Error messages** you've seen
5. **Steps you've already tried** from this troubleshooting guide
6. **Browser and device** you're using

## Prevention Tips

### Regular Maintenance
1. **Check your notification settings** monthly
2. **Update your contact information** when it changes
3. **Test notifications** periodically by having someone mention you

### Best Practices
1. **Start with basic settings** and add complexity gradually
2. **Use web notifications** as your primary channel
3. **Enable email** as a backup for important notifications
4. **Use SMS/WhatsApp** sparingly for urgent items only

### Staying Informed
1. **Ask your administrator** about notification system updates
2. **Report issues promptly** to help maintain system reliability
3. **Share solutions** with team members who have similar problems

## Related Resources

- [Manage Notification Preferences](manage-notification-preferences.md) - Configure your notification settings
- [Email Notification Settings](email-notification-settings.md) - Detailed email configuration
- [Notification Channels](notification-channels.md) - Understanding delivery methods
- [Update Contact Information](update-contact-information.md) - Ensure correct email and phone number