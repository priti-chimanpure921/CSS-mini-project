# CSS Sidebar Mini Project

This is a responsive <b>Sidebar Navigation Menu</b> built using pure HTML and CSS.
The sidebar opens and closes using a checkbox toggle (CSS-only technique).

# Features

🎨 Full-screen background image

📂 Sliding sidebar menu

🔘 Toggle button to open/close sidebar

✨ Smooth CSS transitions

🖱 Hover effects on menu items

🌐 Social media icon section

📱 Full height layout using 100vh

# Technologies Used
<ul>
  <li>HTML5</li>
  <li>CSS3</li>
  <li>Google Fonts (Roboto)</li>
  <li>Font Awesome (for icons)</li>
</ul>

# Key Concepts Used
<b>CSS Reset</b><br>
  body {
      margin: 0;
      padding: 0;
    }
    
<b>Background Image with Cover</b><br>
{
  background: url(photo.jpg); 
  background-size: cover;
}

<b>Sidebar Animation</b><br>
{
  transition: all 0.5s linear;
}

<b>Checkbox Toggle Technique</b><br>
{
  #check:checked ~ .sidebar_menu {
  left: 0;
}<br>
This allows opening and closing the sidebar without JavaScript.

# How to Run the Project
<ul>
  <li>Clone the repository</li>
  <li>Open the project folder</li>
  <li>Open mini_project.html in your browser OR Use Live Server in VS Code</li>
</ul>







