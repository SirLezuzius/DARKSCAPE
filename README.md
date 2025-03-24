# Redmine 6 Dark Theme - Darkscape®

A clean, responsive, and user-friendly theme designed for Redmine 6. This theme enhances the default interface with a modern layout, improved readability, and a more intuitive user experience – ideal for both light and dark environments.

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

bash
Copy
Edit
bundle exec rake tmp:cache:clear
bundle exec rake tmp:sessions:clear
Then restart your web server (e.g., Passenger, Puma, or Apache).

🧪 Tested On

  Redmine version                6.0.4.stable
  Ruby version                   3.1.2-p20 (2022-04-12) [x86_64-linux]
  Rails version                  7.2.2.1
  Environment                    production
  Database adapter               Mysql2

Most major browsers (Chrome, Firefox, Safari)

📸 Screenshots

🛠 Customisation
You're welcome to modify the CSS or images to suit your organisation's branding. Just remember to keep backups if upgrading the theme later.

🤝 Contributing
If you'd like to improve the theme or fix bugs, feel free to fork the repo and submit a pull request.

📄 License
This theme is open source and available under the MIT License.
