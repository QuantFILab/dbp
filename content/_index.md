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
    design:
      min_height: "60vh"
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
      title: "เกี่ยวกับโครงการ"
      subtitle: "การเพิ่มประสิทธิภาพการจัดการหมูหลุมเพื่อความมั่นคงทางอาหาร"
      text: |-
        <div style="font-family: serif; font-size: 1.05rem; line-height: 1.8;">
          โครงการวิจัยนี้มีวัตถุประสงค์เพื่อเพิ่มประสิทธิภาพการเลี้ยงหมูหลุม  
          โดยส่งเสริมการใช้วัสดุรองพื้นจากเศษเหลือทางการเกษตร  
          ร่วมกับจุลินทรีย์ท้องถิ่น (Indigenous Microorganism; IMO)  
          ซึ่งช่วยในการย่อยสลายของเสีย ลดกลิ่นเหม็นในฟาร์ม  
          และสามารถผลิตปุ๋ยหมักคุณภาพสูงได้
          <br><br>
          แนวทางการดำเนินงานครอบคลุมการถ่ายทอดเทคโนโลยีการเลี้ยง  
          การออกแบบโรงเรือน การควบคุมโรค การลดต้นทุนอาหารสัตว์  
          และการแปรรูปผลิตภัณฑ์จากหมูหลุม  
          โดยเน้นการมีส่วนร่วมของเกษตรกรในพื้นที่เป้าหมาย  
          และการพัฒนาเครือข่ายการผลิตแบบยั่งยืนผ่านระบบ PGS  
          (Participatory Guarantee System)
          <br><br>
          <ul style="padding-left: 1.4rem;">
            <li><strong>ระยะเวลาดำเนินการ:</strong> มกราคม 2568 – ธันวาคม 2570</li>
            <li><strong>พื้นที่นำร่อง:</strong> จังหวัดเชียงใหม่ สุรินทร์ และพื้นที่อื่นที่มีความพร้อม</li>
            <li><strong>หัวหน้าโครงการ:</strong> รศ.ดร.วัชรพงษ์ วัฒนกูล (มหาวิทยาลัยราชภัฏเชียงใหม่)</li>
            <li><strong>หน่วยงานสนับสนุน:</strong> สำนักงานพัฒนาการวิจัยการเกษตร (องค์การมหาชน)</li>
            <li><strong>คำสำคัญ:</strong> หมูหลุม, องค์ความรู้, มาตรฐาน, การใช้ประโยชน์, ภาคเหนือ</li>
          </ul>
        </div>
    design:
      columns: '1'



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
      title: 📞 ติดต่อโครงการหมูหลุม
      text: |-
        โครงการวิจัย "การเพิ่มประสิทธิภาพการจัดการการเลี้ยงหมูหลุมที่เหมาะสมสำหรับเกษตรกรในจังหวัดเชียงใหม่เพื่อความมั่นคงทางอาหารของชุมชนท้องถิ่น"  
        โดยได้รับทุนสนับสนุนจากสำนักงานพัฒนาการวิจัยการเกษตร (องค์การมหาชน)
        **หัวหน้าโครงการ:**  
        รศ.ดร.วัชรพงษ์ วัฒนกูล  
        คณะเทคโนโลยีการเกษตร  
        มหาวิทยาลัยราชภัฏเชียงใหม่  
        โทร: 089-755-3989  
        อีเมล: wacharapong.w@cmru.ac.th
      button:
        text: ดาวน์โหลดรายละเอียดโครงการ
        url: /uploads/moo-tech-project.pdf
    design:
      card:
        css_class: "bg-primary-700 text-white text-left p-6 rounded-xl shadow-lg"
        css_style: ""

---
