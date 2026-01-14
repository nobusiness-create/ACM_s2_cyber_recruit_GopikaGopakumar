# Challenge-3

## Challenge Description

The challenge contained txt file with html code in it.The html had CSS, Java Script applied.The flag was hidden as numerous base64 which had to be decoded in the Inspect.

---

## Analysis:

I inspected the HTML source and developer tools identifying URL encoding and reversal techniques.

I analyzed the JavaScript logic to understand the valid Base64 fragments. Using that, I filtered out the invalid fragments from the correct ones.
Only four fragments were decoded cleanly into ordered parts which together formed the flag.

---

## Tools

Inspect
atob(" ")

---


## Flag: 

flag{PArt1_PArt2_PArt3_PArt4}

---