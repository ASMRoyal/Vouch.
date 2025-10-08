<div align="center">
  <img width="832" height="300" alt="Gemini_Generated_Image_p66ycop66ycop66y-ezgif com-resize_1_-removebg-preview" src="https://github.com/user-attachments/assets/82793435-a0ee-4f6d-8c02-61d09757f9c0" />
  <h1>VouchBot: Your Ultimate Discord Vouch System</h1>
  <p>Seamlessly manage seller reputations and build trust within your Discord community.</p>
  <p>
    <img src="https://img.shields.io/discord/1366082447602618440?style=for-the-badge&logo=discord&logoColor=%23ea268e&label=FZ%20ETP&color=%23ea268e&cacheSeconds=3600&link=https%3A%2F%2Fdiscord.gg%2F9hKGaukd2U" alt="Discord">
    <a href="https://vouchbot.org" target="_blank">
      <img src="https://img.shields.io/badge/Website-VouchBot-blueviolet?style=for-the-badge&logo=netlify&logoColor=%23ea268e" alt="VouchBot Website">
    </a>
    <img src="https://img.shields.io/badge/Discord.py-2.3.2-purple.svg?style=for-the-badge&logo=discord" alt="Discord.py Version">
    <img src="https://img.shields.io/github/stars/ASMRoyal/Vouch.?style=for-the-badge&color=purple" alt="GitHub Stars">
  </p>
</div>

---

## About VouchBot

VouchBot is a powerful and intuitive Discord bot designed to help communities establish and maintain a reliable vouching system for sellers and service providers. It allows users to leave detailed feedback, rate transactions, and build a transparent reputation for trusted members. With features like customizable profiles, daily leaderboards, and robust moderation tools, VouchBot ensures a fair and secure environment for all.

### Key Features:

* **User Profiles:** Each user gets a customizable profile displaying their vouch history, average rating, and trust level.
* **Vouch Submission:** Easy-to-use commands and interactive dropdowns for submitting vouches with product, price, rating, and proof.
* **Reputation System:** Calculates a trust score based on received vouches, distinguishing between trusted, neutral, and untrusted users.
* **Seller Ranks:** Automatic ranking system based on vouch count, encouraging sellers to provide excellent service.
* **Daily Leaderboards:** Showcases top sellers in your server, updated daily.
* **Advanced Search:** Search vouches by seller, product, or vouch ID.
* **Moderation Tools:** Commands for removing fake vouches, blacklisting users (globally or per server), and reporting scammers.
* **Configurable Settings:** Admins can set up vouch channels, modlog channels, role restrictions, minimum account age for vouching, and manage a list of approved sellers for dropdown menus.
* **Scammer Reporting:** Dedicated system for reporting suspicious users with moderation review.

---

## Commands

VouchBot uses slash commands for easy interaction. Here's a quick overview of the main commands:

### User Commands

* `/vouch <product> <price> <seller> [rating] [reason] [proof]`: Submit a vouch for a seller.
* `/profile [user]`: View your or another user's vouch profile.
* `/settings [banner_url] [profile_picture_url] [bio] [reset]`: Customize your profile display.
* `/search [user] [product] [vouch_id]`: Search for specific vouches.
* `/rank`: See your current vouch rank and all available ranks.
* `/removeownvouch <vouch_id>`: Remove a vouch you previously submitted.
* `/reportscammer <user> <reason> [proof]`: Report a user as a scammer.

### Admin/Moderation Commands (Requires `Administrator` permission or configured admin roles)

* `/setvouchconfig <vouch_channel> [modlog_channel] [use_role_restriction] [allowed_role] [min_account_age_days]`: Set up vouching channels and restrictions for your server.
* `/setleaderboardchannel <channel>`: Set the channel for daily leaderboard posts.
* `/testleaderboard`: Manually trigger a leaderboard post.
* `/removevouch <vouch_id> <reason> [proof]`: Remove a specific vouch.
* `/blacklist <user> <action>`: Blacklist or unblacklist a user from using the vouch system on your server.
* `/globalblacklist <user> <action>`: Globally blacklist or unblacklist a user from using the vouch system across all servers (Owner/Admin/Developer only).
* `/serverblacklist <guild_id> <action>`: Blacklist or unblacklist a server from using the bot (Owner/Admin/Developer only).
* `/setadmin <roles> <action>`: Add, remove, or list roles that can use moderation commands like `/removevouch` and `/blacklist`.
* `/managesellers [user] [action]`: Add, remove, or list sellers who can be vouched for via the dropdown menu.
* `/create`: Creates an interactive dropdown message for vouching in the current channel.
* `/restore`: Restore all saved vouches to the configured vouch channel.

---

## Contributing

We welcome contributions! If you have suggestions for new features, bug fixes, or improvements, feel free to:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/your-feature`).
3.  Make your changes.
4.  Commit your changes (`git commit -m 'feat: Add new feature'`).
5.  Push to the branch (`git push origin feature/your-feature`).
6.  Open a Pull Request.

Please ensure your code adheres to the existing style and includes relevant comments.

---

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.
*(Note: You'll need to add a `LICENSE` file to your repository if you haven't already.)*

---

## Support

If you encounter any issues or have questions, feel free to open an issue on the GitHub repository or visit our website: [vouchbot.org](https://vouchbot.org).

---

<div align="center">
  <p>Made with ❤️ by FZ Enterprise</p>
</div>
