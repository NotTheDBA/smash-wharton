# Terminal - SSH Commands
#### Follow these instructions to set up your SSH Key.  We will only need to do this once.

Open the terminal window
```CTRL+` ```

Paste the text below, substituting in **your** GitHub email address.

`ssh-keygen -t rsa -b 4096 -C "your_email@example.com"`

This creates a new _SSH_ key, using the provided email as a label.  And SSH key is a file that acts like a password when you work with Github.

##### Generating public/private rsa key pair.

When you're prompted to "Enter a file in which to save the key," just press Enter. This accepts the default file location.

`Enter a file in which to save the key (/c/Users/you/.ssh/id_rsa):[Press enter]`


Now, when you are prompted for a password, just hit Enter twice more.  

`
Enter passphrase (empty for no passphrase): [Type a passphrase]
Enter same passphrase again: [Type passphrase again]
`

You can run these steps again later on if you want to add a password for extra security, after you are comfortable using Git commands.  Adding a password means you will have to enter that password every time you add or retrieve files from Github.


#### Adding your SSH Key to Github

##### Copy the SSH key to your clipboard.

Use this terminal command to copy the contents of your new SSH Key to your clipboard (that is, in memory!)

`clip < ~/.ssh/id_rsa.pub`

* ##### Settings link in the user bar
In the upper-right corner of any page, click your profile photo, then click Settings.

![userbar-account-settings](/assets/userbar-account-settings_y6wpu158s.png)

* ##### Authentication keys
In the user settings sidebar, click SSH and GPG keys.

![settings-sidebar-ssh-keys](/assets/settings-sidebar-ssh-keys_6pi183b4v.png)

* ##### SSH Key button

Click New SSH key or Add SSH key.

![ssh-add-ssh-key](/assets/ssh-add-ssh-key.png)

* ##### Title Field

In the "Title" field, add a descriptive label for the new key. For example, you might use **SMASH Wharton 2018**.

* ##### The key field
Paste your key into the "Key" field.   (You can use `CTRL+V` to paste)

![ssh-key-paste](/assets/ssh-key-paste.png)

* ##### The Add key button
Click Add SSH key.

![ssh-add-key](/assets/ssh-add-key.png)

* ##### Password dialog
If prompted, confirm your GitHub password.

![sudo_mode_popup](/assets/sudo_mode_popup.png)
