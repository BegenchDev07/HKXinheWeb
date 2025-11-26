---
enable: true # التحكم في ظهور هذا القسم في جميع الصفحات التي يُستخدم فيها
title: "هل لديك مشروع في ذهنك؟"
description: "رائع! نحن متحمسون للاستماع إليك وبدء شيء جديد معك"

# image: "/images/about-us/about-one.jpg"
# imagePosition: "left" # اختر بين "left" أو "right"

map:
  enable: true
  position: "right" # اختر بين "left" أو "right"
  title: "خريطة نيو وورك سيتي"
  url: https://maps.google.com/maps?width=100%25&amp;height=600&amp;hl=ar&amp;q=1%20Grafton%20Street,%20Dublin,%20Ireland+(اسم%20شركتي)&amp;t=&amp;z=14&amp;ie=UTF8&amp;iwloc=B&amp;output=embed

form:
  emailSubject: "إرسال نموذج جديد من موقع فوليكس" # موضوع البريد لكل إرسال
  submitButton:
    label: "إرسال الرسالة"
  inputs:
    - label: ""
      placeholder: "الاسم الكامل *"
      name: "الاسم الكامل"
      required: true
      halfWidth: true
      defaultValue: ""
    - label: ""
      placeholder: "البريد الإلكتروني *"
      name: "البريد الإلكتروني"
      required: true
      type: "email"
      halfWidth: true
      defaultValue: ""
    - label: ""
      placeholder: "الموضوع *"
      name: "الموضوع"
      required: false
      halfWidth: true
      dropdown:
        type: ""
        search:
          placeholder: ""
        items:
          - label: "طلب عام"
            value: "طلب عام"
            selected: false
          - label: "فرصة شراكة"
            value: "فرصة شراكة"
            selected: false
          - label: "فرصة استثمار"
            value: "فرصة استثمار"
            selected: false
    - label: ""
      placeholder: "الموضوع مع البحث *"
      name: "الموضوع مع البحث"
      required: false
      halfWidth: true
      dropdown:
        type: "search"
        search:
          placeholder: "الموضوع مع البحث"
        items:
          - label: "طلب عام"
            value: "طلب عام"
            selected: false
          - label: "فرصة شراكة"
            value: "فرصة شراكة"
            selected: false
          - label: "فرصة مهنية"
            value: "فرصة مهنية"
            selected: false
          - label: "فرصة استثمار"
            value: "فرصة استثمار"
            selected: false
          - label: "طلب إعلامي"
            value: "طلب إعلامي"
            selected: false
    - label: ""
      tag: "textarea"
      defaultValue: ""
      rows: "2"
      placeholder: "كيف يمكننا مساعدتك *"
      name: "الرسالة"
      required: true
      halfWidth: false
    - label: "بحث جوجل"
      checked: false
      name: "مصدر المستخدم"
      required: true
      groupLabel: "كيف سمعت عنا؟"
      group: "source"
      type: "radio"
      halfWidth: true
      defaultValue: ""
    - label: "وسائل التواصل الاجتماعي"
      name: "مصدر المستخدم"
      required: true
      groupLabel: ""
      group: "source"
      type: "radio"
      halfWidth: true
      defaultValue: ""
    - label: "أوافق على الشروط والأحكام وكذلك [سياسة الخصوصية](/)."
      id: "privacy-policy"
      name: "موافقة الخصوصية"
      value: "موافق"
      checked: false
      required: true
      type: "checkbox"
      halfWidth: false
    - note: success
      parentClass: "hidden text-sm message success"
      content: "تم استلام رسالتك بنجاح! سنرد عليك في أقرب وقت ممكن."
    - note: deprecated
      parentClass: "hidden text-sm message error"
      content: "حدث خطأ! يرجى استخدام هذا البريد - [HK Xinhe Group-astro-theme@gmail.com](mailto:HK Xinhe Group-astro-theme@gmail.com) لإرسال طلب الدعم!"
---
