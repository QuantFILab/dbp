---
title: ""
date: 2025-05-21
type: landing

design:
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: '<span class="text-4xl md:text-6xl font-semibold tracking-wide text-gold-400">โครงการหมูหลุม</span>'
      subtitle: '<span class="text-xl md:text-2xl font-light text-white/80 mt-2 block">เทคโนโลยีเลี้ยงหมูแนวใหม่ เพื่อสุขภาพ สิ่งแวดล้อม และเศรษฐกิจชุมชน</span>'
      text: |
        <div class="max-w-2xl mx-auto mt-6 text-lg md:text-xl text-white/90 leading-relaxed">
        โครงการนี้มุ่งเน้นการพัฒนาและถ่ายทอดองค์ความรู้ในการเลี้ยงหมูหลุมด้วยวัสดุท้องถิ่นและจุลินทรีย์ธรรมชาติ  
        เพื่อลดกลิ่น ลดต้นทุน และเพิ่มรายได้ให้เกษตรกรรายย่อยอย่างยั่งยืน
        </div>
      button:
        text: 📄 ดาวน์โหลดคู่มือเทคโนโลยี
        url: uploads/moo-tech-project.pdf
    design:
      css_class: "text-center px-6 py-24 md:py-32"
      min_height: "70vh"
      background:
        color: black
        image:
          filename: pig-tech-bg.svg
          filters:
            brightness: 0.8
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
      columns: 2

  - block: collection
    id: news
    content:
      title: ข่าวสารจากโครงการ
      subtitle: ''
      text: ''
      page_type: post
      count: 3
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
