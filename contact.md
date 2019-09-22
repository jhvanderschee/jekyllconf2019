---
layout: page
forms:
  - to: jhvanderschee@gmail.com
    subject: New submission!
    redirect: /jekyllconf2019/
    form_engine: cloudcannon
    placeholders: false
    fields:
      - name: name
        input_type: text
        placeholder: Name
        required: true
      - name: email
        input_type: email
        placeholder: Email address
        required: true
      - name: sex
        input_type: radio
        placeholder: male
        required: true
      - name: sex
        input_type: radio
        placeholder: female
        required: true
      - name: message
        input_type: textarea
        placeholder: Message
        required: false
      - name: terms
        input_type: checkbox
        placeholder: I accept the terms and conditions
        required: true
      - name: submit
        input_type: submit
        placeholder: Submit form
        required: true
---

# Contact

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi sed rhoncus ipsum. Proin rutrum orci eu diam elementum maximus. Nulla rhoncus iaculis ultricies. Donec dictum id urna sit amet facilisis.
