# 📧 Contact Form with Email

A simple **Contact Form project in PHP** that allows users to submit their details and send messages via email using the `mail()` function.

---

## 🚀 Features

* User-friendly contact form
* Input fields:

  * Name
  * Email
  * Message
* Server-side validation
* Email sending using PHP `mail()`

---


## 📁 Project Structure

```
contact-form/
│── index.html     # Frontend form
│── send.php       # Backend email logic
```

---

## ⚙️ How It Works

1. User fills out the contact form.
2. Form data is sent via `POST` to `send.php`.
3. PHP validates the input.
4. Email is sent using the `mail()` function.

---

## ▶️ Setup Instructions

### 1. Clone or Download

```bash
git clone https://github.com/yogeshkumarsaini/contact-form.git
```

### 2. Configure Email

Open `send.php` and update:

```php
$to = "yogeshkumarsaini1085@gmail.com";
```

### 3. Run Project

* Place project in `htdocs` (XAMPP) or `www` (WAMP)
* Start Apache server
* Open in browser:

```
http://localhost/contact-form/
```

---

## ⚠️ Important Notes

* PHP `mail()` may **not work on localhost** without configuration.
* Works properly on **live hosting servers**.

---

## 🔐 Security Features

* Input sanitization using `htmlspecialchars()`
* Email validation using `filter_var()`



