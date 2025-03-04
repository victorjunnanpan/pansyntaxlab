---
title: Team Introduction  # 页面标题
date: 2022-10-24       # 创建日期
 
type: landing          # 页面类型，保持为 landing
 
sections:
  # 第1部分：欢迎标题和简介
  - block: hero
    content:
      title: Welcome to Our Team
      subtitle: Innovating the Future of Artificial Intelligence
      text: |-
        We are a group of passionate researchers and engineers at Stanford University, working on cutting-edge AI technologies. Learn more about our mission and the people behind it.
      cta:  # Call-to-Action 按钮（可选）
        label: Meet the Team
        url: '#meet-the-team'  # 跳转到页面内的某个部分
    design:
      columns: '1'
      background:
        image:
          filename: team-background.jpg  # 背景图片，需放在 static/images/
          filters:
            brightness: 0.8
          parallax: false
          position: center
          size: cover
        text_color_light: true  # 如果背景深色，文字用浅色
      spacing:
        padding: ['40px', '0', '40px', '0']
 
  # 第2部分：团队亮点
  - block: features
    id: meet-the-team  # 用于 CTA 跳转
    content:
      title: Our Strengths
      subtitle: What Makes Us Unique
      items:
        - name: Research Excellence
          description: Pioneering advancements in AI and robotics.
          icon: robot
          icon_pack: fas
        - name: Collaborative Spirit
          description: Working together to solve complex problems.
          icon: users
          icon_pack: fas
        - name: Global Impact
          description: Innovating for a better tomorrow.
          icon: globe
          icon_pack: fas
    design:
      columns: '2'  # 两列布局
      spacing:
        padding: ['20px', '0', '20px', '0']
 
  # 第3部分：详细介绍（自由文本）
  - block: markdown
    content:
      title: About Us
      subtitle: ''
      text: |-
        Our team at Stanford AI Lab focuses on distributed robotics, mobile computing, and programmable matter. Led by experts like Alice Wu and Zetao Xu, we develop self-reconfiguring robots and mobile sensor networks. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed neque elit, tristique placerat feugiat ac, facilisis vitae arcu.
    design:
      columns: '1'
      css_class: fullscreen
---
