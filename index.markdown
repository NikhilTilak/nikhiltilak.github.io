---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
---

<!-- <body>
    <div style="display: flex;">
      <img src="../assets/profpic.jpg" alt="Your Profile Picture" style="width: 200px;">
      <div style="margin-left: 20px;">
        <h1>Hello! My name is Nikhil Tilak.</h1>
        <p>I recently earned a PhD in Physics from Rutgers University, New Jersey, USA. I will be starting a Postdoctoral position soon.
        I am looking for new opportunities at the intersection of Physics, Engineering, and Data Science. 
        To learn more about me, press the tabs above.
        My socials are linked below. </p>
      </div>
    </div>
</body> -->

<html>
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body {
      font-family: Arial, sans-serif;
    }

    .container {
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
      padding: 20px;
    }

    .profile-pic {
      width: 200px;
      margin-bottom: 20px;
    }

    @media (min-width: 768px) {
      .container {
        flex-direction: row;
        justify-content: center;
        text-align: left;
      }

      .profile-pic {
        margin-bottom: 0;
      }

      .profile-info {
        margin-left: 20px;
        text-align: left;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <img src="../assets/profpic.jpg" alt="Your Profile Picture" class="profile-pic">
    <div class="profile-info">
      <h1>Hello! My name is Nikhil Tilak.</h1>
      <p>I'm a Postdoc in Physics with 8+ years of research experience. I'm an expert at device fabrication using e-beam lithography and characterization via tunneling and transport measurements. I'm highly skilled at analyzing data and summarizing findings. Furthermore, I'm experienced in numerical and machine learning techniques using Python and always working to expand my skill set. I'm currently open to process/yield engineering roles in the semiconductor industry as well as data scientist positions.
      My CV is linked above. Feel free to reach out to me on LinkedIn or via email if you have a suitable opportunity and would like to know more.</p>
    </div>
  </div>
</body>
</html>
