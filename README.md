# 📚 BOOKEN - Your Digital Bookshelf

![Books Banner](https://img.shields.io/badge/Booken-Your%20Literary%20Journey%20Begins%20Here-blue?style=for-the-badge)

> *"A reader lives a thousand lives before he dies. The man who never reads lives only one."* - George R.R. Martin

## ✨ Welcome to Booken!

Dive into the world of literature with **Booken** - not just an eCommerce platform, but a gateway to countless adventures waiting to be discovered. Our sleek, modern interface connects book lovers with their next favorite read in just a few clicks.

## 🌟 Features That Delight

🔐 **Seamless Authentication**
- Login/logout with secure session management
- "Remember me" feature for returning bookworms

🛡️ **Bank-Grade Security**
- Password protection with MD5 hashing
- Prepared statements to keep your data safe

📱 **Responsive Design**
- Beautiful Bootstrap styling that looks perfect on any device
- Intuitive navigation for the best user experience

🛒 **Shop With Confidence**
- Browse our extensive collection of titles
- Add favorites to your cart with a simple click

## 🚀 Embark on Your Journey

Getting started with Booken is as easy as opening a book:

1. 📥 Clone this magical repository to your machine
2. 🖥️ Set up your wizarding environment (XAMPP/WAMP/MAMP)
3. 🧙‍♂️ Cast the SQL spell (`DB file/login_with_prepared_statement.sql`) into your database
4. 📁 Place the Booken tome in your web server's sacred directory (e.g., `htdocs`)
5. 🌐 Open the portal via `http://localhost/Booken/index.html`

## 🔮 Database Enchantment

```
📊 DATABASE CONFIGURATION
┌────────────────────────────────────────┐
│ Host: localhost                        │
│ Username: root                         │
│ Password: (Your Secret Spell)          │
│ DB Name: login_with_prepared_statement │
└────────────────────────────────────────┘
```

Adjust the mystic connections in `conn/connection.php`:

```php
<?php 
$host = "localhost";  // Your magical realm
$user = "root";       // Your wizard name
$db_password = "";    // Your secret incantation
$db_name = "login_with_prepared_statement";  // Your tome of knowledge

$conn = mysqli_connect($host, $user, $db_password, $db_name);
if($conn){
    // The connection spell worked!
}
else{
    echo "The spell failed! Check your incantation.";
}
?>
```

## 🗺️ Navigating the Realms

### 🏠 Main Realm
- Enter through the main gates: `http://localhost/Booken/index.html`
- Discover featured collections and magical navigation

### 🔑 Secret Chamber
- Unlock the login portal: `http://localhost/Booken/index.php`
- Default access scroll:
  - 📧 Wizard Email: admin@gmail.com
  - 🔒 Incantation: admin
- Check "Remember me" to leave breadcrumbs for your return

### 🏰 Your Personal Library
- After successful authentication, your dashboard awaits
- A personalized welcome and the option to venture elsewhere

## 📜 Map of the Realm

```
BOOKEN DIRECTORY STRUCTURE
┌─📄 index.html        → The grand entrance
├─📄 index.php         → The login scroll
├─📄 login.php         → The authentication spell
├─📄 dashboard.php     → Your personal chamber
├─📄 logout.php        → The exit portal
├─📁 conn/             → Connection enchantments
├─📁 inc/              → Shared scrolls
├─📁 assets/           → Visual treasures
└─📁 DB file/          → The knowledge foundation
```

## 🛡️ Security Spells

- Password scrolls are protected with MD5 enchantments (For legendary protection, consider upgrading to bcrypt in production)
- User journeys are tracked securely
- Our database is fortified against SQL injection dark magic

## 🆘 Troubleshooting

Lost in the labyrinth? Try these solutions:

1. 🔍 Verify your connection scrolls in `conn/connection.php`
2. ⚡ Ensure your magical servers (web & MySQL) are awake
3. 📚 Check that you've properly transcribed the SQL tome

---

<p align="center">📚 <b>Happy Reading!</b> 📚</p>
<p align="center">Crafted with ❤️ for book lovers everywhere</p> 
