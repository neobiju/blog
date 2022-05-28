---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Cryptography"
summary: "Encryption algorithms"
authors: [neobiju]
tags: []
categories: []
date: 2022-05-28T21:16:41+03:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
[Cryptography github page](https://github.com/neobiju/cryptography)

# Modern cryptography
<hr>
Modern cryptography is the backbone of computer security. It is based on various mathematical concepts such as number theory, computational complexity theory, probability theory.
Today, cryptographic protection methods are used not only to encrypt transactions and control the production of cryptocurrencies, but also ensure the safe operation of banking systems, plastic cards, ATMs, e-commerce, and wireless devices.

# Basic concepts of cryptography
<hr>
The main component of cryptography is encryption. Messages are encrypted and decrypted using complex algorithms created by a combination of computer science and mathematics.

Encryption uses an algorithm and a key to convert the input into an encrypted output. This security method allows messages to be viewed exclusively by the sender and recipient, since the encrypted information can only be read by someone who has the secret key to convert the message to plain text.

# Symmetric encryption
<hr>
It is the simplest algorithm. Cryptographers often refer to it as a cryptographic secret key (SKC) or a shared key, since information is encrypted and decrypted using the same key. Symmetric encryption implies that the secret digital key must be known to both the recipient and the sender.

# Asymmetric encryption
<hr>
This algorithm is widely used in the World Wide Web. It is also called Public Key Cryptography (PKC). The PKC algorithm uses two keys: public and private.

    Open may be known to many. It is impossible to decrypt data using it. For example, an email address is a public key.
    The private is secret, used to decrypt the message, never revealed to the other party. For example, the email account password is the key to opening emails.
    It doesn't matter which key is applied first, but both are needed to work.
    Data can be encrypted with a public or private key.

