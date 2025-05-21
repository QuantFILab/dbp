---
title: ""
date: 2025-05-21
type: landing

design:
  spacing: "6rem"

sections:
- block: hero
  content:
    title: "โครงการหมูหลุม"
    subtitle: "การเลี้ยงหมูแนวใหม่เพื่อความยั่งยืน ไม่พึ่งพาสารเคมี"
    text: |
      โครงการนี้มุ่งเน้นการยกระดับการเลี้ยงหมูโดยใช้เทคโนโลยีและธรรมชาติ  
      ลดต้นทุน เพิ่มผลผลิต และเป็นมิตรต่อสิ่งแวดล้อม
    button:
      text: ดาวน์โหลดเอกสารโครงการ
      url: uploads/moo-tech-project.pdf
  design:
    css_class: "dark rounded-xl shadow-xl backdrop-blur-md px-6 py-12 text-white text-center"
    background:
      color: black
      image:
        filename: pig-tech-bg.svg
        filters:
          brightness: 0.6  # Slightly darker to make text pop
          opacity: 0.95    # Allow soft transparency
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
    id: papers
    content:
      title: งานวิจัยที่เกี่ยวข้อง
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 3

  - block: collection
    id: talks
    content:
      title: กิจกรรมภาคสนาม
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 3

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
