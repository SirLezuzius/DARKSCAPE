# Redmine 6 Dark Theme - Darkscape®

A clean, responsive, and user-friendly theme designed for Redmine 6. This theme enhances the default interface with a modern layout, improved readability, and a more intuitive user experience.

## Overview

This theme was built with usability and clarity in mind. It features:

- Modern look and feel - Sleek layout with updated styles
- Responsive design - Works well on desktops and mobile devices
- Improved navigation - Clearer menus and buttons

Compatible with Redmine 6.x

## Installation

Follow the steps below to install the theme on your Redmine 6 instance:

## 1. Locate your Redmine themes directory

Navigate to the Redmine installation directory. Inside it, you should find a folder named `themes`. Example path:

"/opt/redmine/themes/"

## 2. Copy the Darkscape folder into the "themes" folder and enjoy.


## 3. Set the theme in Redmine
Log in to Redmine as an administrator
Go to Administration > Settings > Display
Choose your new theme from the Theme dropdown
Save changes

## 4. Restart Redmine (if needed)
Depending on your setup, you may need to restart your Redmine server or clear the cache:

bash<br>
Copy<br>
Edit<br>
bundle exec rake tmp:cache:clear<br>
bundle exec rake tmp:sessions:clear<br>
Then restart your web server (e.g., Passenger, Puma, or Apache).

🧪 Tested On

  Redmine version = 6.0.4.stable<br>
  Ruby version = 3.1.2-p20 (2022-04-12) [x86_64-linux]<br>
  Rails version = 7.2.2.1<br>
  Database adapter = Mysql2

Most major browsers (Chrome, Firefox, Safari)

📸 Screenshots

![image](https://github.com/user-attachments/assets/b3895b8c-31eb-46de-91e0-b2db603d039c)
![image](https://github.com/user-attachments/assets/efbd4375-a469-4e4c-817f-9af8ec4ad00c)
![image](https://github.com/user-attachments/assets/18698459-855c-42fc-be03-01d1be2bfb0a)



🛠 Customisation
You're welcome to modify the CSS or images to suit your organisation's branding. Just remember to keep backups if upgrading the theme later.


📄 License
This theme is open source and available under the MIT License.
