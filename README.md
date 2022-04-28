```mermaid
 classDiagram
      Animal <|-- Duck
      Animal <|-- Fish
      Animal <|-- Zebra
      Animal : +int age
      Animal : +String gender
      Animal: +isMammal()
      Animal: +mate()
      class Duck{
          +String beakColor
          +swim()
          +quack()
      }
      class Fish{
          -int sizeInFeet
          -canEat()
      }
      class Zebra{
          +bool is_wild
          +run()
      }
```     
      

<p><img src="images/test.png" /></p>

<table>
  <tbody>
    <tr>
      <td><a href="https://github.com/Dantalor/markdown-portfolio/edit-diagram.html?repo=markdown-portfolio&amp;path=test.png" target="_blank">Edit</a></td>
      <td><a href="https://app.diagrams.net/#Uhttps%3A%2F%2Fraw.githubusercontent.com%2FDantalor%2Fmarkdown-portfolio%2Fmain%2Ftest.png" target="_blank">Edit As New</a></td>
      <td><a href="https://app.diagrams.net/#HDantalor%2Fmarkdown-portfolio%2Fmain%2Ftest.png" target="_blank">Edit in diagrams.net</a></td>
    </tr>
  </tbody>
</table>



![https://app.diagrams.net/?mode=github](images/test.svg)


![https://app.diagrams.net/?mode=github](images/test.drawio)
