---
title: ""
date: 2025-05-21
type: landing

design:
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: |
        โครงการ “เทคโนโลยีการเลี้ยงหมูหลุม” มุ่งเน้นการพัฒนาระบบการเลี้ยงหมูที่ยั่งยืน  
        ด้วยการใช้เทคโนโลยีและองค์ความรู้ที่เป็นมิตรต่อสิ่งแวดล้อม  
        เพิ่มประสิทธิภาพการผลิตและลดต้นทุนของเกษตรกรไทย
      button:
        text: ดาวน์โหลดเอกสารโครงการ
        url: uploads/moo-tech-project.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: pig-tech-bg.svg
          filters:
            brightness: 0.5  # darkens background for better white text contrast
          size: cover
          position: center
          parallax: false


  - block: markdown
    content:
      title: '🐷 เกี่ยวกับโครงการหมูหลุม'
      subtitle: ''
      text: |-
        โครงการนี้พัฒนาเพื่อตอบโจทย์ปัญหาการเลี้ยงหมูในชุมชน โดยเน้นการเลี้ยงหมูที่ประหยัดต้นทุน  
        ลดกลิ่นเหม็น ไม่ก่อมลพิษ และสามารถบริหารจัดการเองได้โดยเกษตรกรรายย่อย  
        
        - **ระยะเวลาดำเนินการ:** มกราคม 2568 – ธันวาคม 2570  
        - **พื้นที่นำร่อง:** จังหวัดลำพูน เชียงใหม่ และนครปฐม  
        - **ผู้รับผิดชอบ:** ดร.ภาสิน มารุปานทร

  - block: collection
    id: publications
    content:
      title: งานวิจัยที่เกี่ยวข้อง
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: บทความล่าสุด
      text: ""
      filters:
        folders:
          - post
        exclude_featured: false
    design:
      view: date-title-summary

  - block: collection
    id: events
    content:
      title: กิจกรรมภาคสนาม
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1

  - block: collection
    id: news
    content:
      title: ข่าวสารจากโครงการ
      subtitle: ''
      text: ''
      page_type: post
      count: 5
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      offset: 0
      order: desc
    design:
      view: date-title-summary
      spacing:
        padding: [0, 0, 0, 0]

  - block: cta-card
    demo: false
    content:
      title: 📞 ติดต่อสอบถามเพิ่มเติม
      text: |-
        ศูนย์พัฒนาเทคโนโลยีการเกษตรอัจฉริยะ  
        คณะเกษตรศาสตร์ มหาวิทยาลัยเทคโนโลยีแห่งประเทศไทย  
        โทร: 02-123-4567  
        อีเมล: info@smartagri.ac.th
      button:
        text: เยี่ยมชมเว็บไซต์หลัก
        url: https://yourdomain.com/project/tech-moo/
    design:
      card:
        css_class: "bg-primary-700"
        css_style: ""
---
