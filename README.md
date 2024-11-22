# Styleguide
<h1>Overview</h1>
This repo contains the shared stylesheet for our project. The stylesheet includes main elements of the house style like colors, typography, and form components. Later, we might add more elements as we go further in the sprint. We also created a Figma [Styleguide](https://github.com/yamenAl/look-and-feel-corporate-identity/issues/10) Template to plan and visualize the design structure before coding.<be>
<img src="https://github.com/user-attachments/assets/00fbd93e-7c2d-4329-becc-7185f8161ae1" width="600" />


<h2>File Structure</h2>
index.html: Test and showcase the styleguide components.
qatarmuseums.css: Main CSS file for the shared styleguide. 
<ul><li>
1. Colors
Basic colors for the house style:
<p>
.main-color-white{
    background-color: var(--main-white);
}<br>
.main-color-black{
    background-color: var(--main-black);
}<br>
.accent-color-button{
    background-color: var(--accent-grey);
}<br>
.main-button-color{
    background-color: var(--accent-yellow);
}
..and more..
</p>
<img src="https://github.com/user-attachments/assets/e6068621-2481-4789-bb18-fc74d62a74b8" width="100" />
</li><br><li>
2. Typography
Set custom fonts for body and input:<br>
@layer styleguide {
  html, body {
    scroll-behavior: smooth;
  }
</li><br>
<li>3. Form Elements
Style for inputs and buttons:<br>
</bra>
  <spam>
.button{
    --spacing:0.5rem;<br>
    background-color: light-dark(var(--light-button), var(--dark-button));<br>
    color: light-dark(var(--dark), var(--light));<br>
    padding: var(--spacing);<br>
    margin: var(--spacing);<br>

    &:hover{
        background-color: light-dark(var(--light-hover-button), var(--dark-hover-button));
        color: light-dark(var(--light-hover-button-text), var(--dark-hover-button-text));
    }  
}</spam>
<img src="https://github.com/user-attachments/assets/fe713017-33d0-4529-96f7-1a735013f687" width="300" /></li>
</ul>


<h2>Collaboration</h2>
One team member forks the repo and add all team members as collaborators.<br>
Everyone clones the repo and works on their own branch.<br>
Push changes to the shared repo and use GitHub Issues to track updates.



## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).

