# Dom Manipulation Assignment

1. Webiste Name: [Dev To](https://dev.to/)

### Topics

    - Query Selctory, Inner HTML

### Sample Image

![Sample One](./Pic1.png)

### Tasks

        Target the Top description div and change the DEV Community to <Your_Name> and description to your passion

### Output

![Output](./Pic2.png)

### Answer

    document.querySelector('.side-bar .crayons-card .crayons-subtitle-2').innerHTML = 'iNeuron'
    document.querySelector('.side-bar .crayons-card .color-base-70').innerHTML = 'I Write Code'

2. Website Name: [Apple](https://support.apple.com/en-in)

### Task

![Store](./Picture_3.png)

### Fetch all the product name and store in an array

### Output

['iPhone', 'Mac', 'iPad', 'Watch', 'AirPods', 'Music', 'TV']

### Answer
    let a = document.querySelectorAll('.as-imagegrid-item .as-imagegrid-item-title ')
    let b =[]; 
    for (let index = 0; index < bound; index++) {
        b.push(a[index].innerText.split('\n')[0])
    }


3. Webiste Name: [Youtube Support](https://support.google.com/youtube/)

### Topics

    - Get Element By Id, Create Element, Create Text Node, Append Child

### Sample Image

![Sample One](./Pic4.png)

### Tasks

     Add another FAQ 'My New FAQ' to the list

### Output

![Output](./Pic5.png)

### Answer
    let a = document.createElement('section')
    a.className = 'parent'
    let b = document.createElement('h3')
    b.role="button"
    b.textContent='My New FAQ'
    a.appendChild(b)
    document.querySelector('.no-article-survey .accordion-homepage').appendChild(a)

4. Webiste Name: [OnePlus](https://www.oneplus.in/support)

### Topics

     Query Selector, InnerText

### Sample Image

![Sample One](./Pic6.png)

### Tasks

      Change the contact number

### Output

![Output](./Pic7.png)

### Answer
    document.querySelector('.customer-support .one-tel-number ').innerText = '+91 6366256686'

5. Webiste Name: [Samsung](https://www.samsung.com/in/offer/online/samsung-fest/)

### Topics

       getElementById, createElement, InnerText, append, setAttribute

### Sample Image

![Sample One](./Pic8.png)

### Tasks

     Target the main div of card and change the Button text to Check out

### Output

![Output](./Pic9.png)

### Answer

    let a = document.querySelectorAll('.addcartdata')
    for (let i = 0; i<a.length ; i++) {
        a[i].innerText = 'Buy now'
    }

6. Webiste Name: [Adidas](https://www.adidas.co.in/)

### Topics

    -   Query Selector, Event listeners, Changing Styles

### Sample Image

![Sample One](./Pic10.png)

### Tasks

     Target the search box and on hover change thebackground color to red.

### Output

![Output](./Pic11.png)

### Answer

    var a = document.querySelector('.searchinput___19uW0')
    a.addEventListener('mouseenter' , () => { a.style.backgroundColor = '#E21717'})
    a.addEventListener('mouseleave' , () => { a.style.backgroundColor = '#f1f1f1'})


7. Webiste Name: [MDN Web Docs](https://developer.mozilla.org/en-US/)

### Topics

       Form, Value, Submit

### Sample Image

![Sample One](./Pic12.png)

### Tasks

     To Search a topic in the MDN Search bar.
     First add a text to search in the search bar and then hit the submit search button to search the docs using DOM

### Output

![Output](./Pic13.png)

### Answer

    document.querySelector('#hp-search-input').value = 'CSS Selectors'
    document.querySelector('.search-button').click()

8. Webiste Name: [Google](https://www.google.com/)

### Topics

       Remove Elements

### Sample Image

![Sample One](./Pic14.png)

### Tasks

     Remove alternate languages from the home page languages listed

### Output

![Output](./Pic15.png)

### Answer

    let a = document.querySelector('#SIvCob')
    let b = document.querySelectorAll('#SIvCob a')
    let i = 1
    for ( c of b) {
        if(i===0) {
            a.removeChild(c)
            i=1
        } else {
            i=0
        }
    }

9. Webiste Name: [Code Wars](https://www.codewars.com/)

### Topics

       Change Font Family, Color of Text.

### Sample Image

![Sample One](./Pic16.png)

### Tasks

    Change the font family of the text to monospace and text color to the logo’s background color.

### Output

![Output](./Pic17.png)

### Answer

    document.querySelector(".text-align-center .text-color-white ").style.fontFamily = "monospace"
    document.querySelector(".text-align-center .text-color-white ").style.color = "#BF3312"


10. Webiste Name: [Freecodecamp](https://www.freecodecamp.org/)

### Topics

       querySelector, mouseover, click eventListener,  callback function, style,

### Sample Image

![Sample One](./Pic18.png)

### Tasks

    Target the button and change background colour on mouseover

### Output

![Output](./Pic19.png)

### Answer
    let a = document.querySelector('.col-sm-offset-1 span.login-btn-text')
    a.addEventListener('mouseenter' , () => { a.style.backgroundColor = '#E21717'})
    a.addEventListener('mouseleave' , () => { a.style.backgroundColor = '#FECC4C'})

11. Webiste Name: [realme](https://www.realme.com/in/)

### Topics

       querySelector,style,background-image

### Sample Image

![Sample One](./Pic20.png)

### Tasks

    change the realme logo to ineuron logo

### Output

![Output](./Pic21.png)

### Answer

    document.querySelector('.icon-logo').style.background = url(...)
    document.querySelector('.icon-logo').style.backgroundSize = "150px"
    document.querySelector('.icon-logo').style.backgroundRepeat = "no-repeat"

12. Webiste Name: [Github](https://github.com/)

### Topics

       querySelector,style,background-Color

### Sample Image

![Sample One](./Pic22.png)

### Tasks

     change the background colour of the button to blue.

### Output

![Output](./Pic23.png)

### Answer

    document.querySelector('.section-button').style.background-Color = 'blue'

13. Webiste Name: [Hackerrank](https://www.hackerrank.com/)

### Topics

       querySelector,innerHtml

### Sample Image

![Sample One](./Pic24.png)

### Tasks

Target the top description and change “Matching developers with great companies” to ‘JSBOOTCAMP“.

### Output

![Output](./Pic25.png)

### Answer
    document.querySelector('.home22-intro-title').innerHTML = 'JSBOOTCAMP'

14. Webiste Name: [Asus](https://www.asus.com/in/)

### Topics

      querySelector,style,font-size

### Sample Image

![Sample One](./Pic26.png)

### Tasks

       change the fontsize of “Hot Deals” to 80px

### Output

![Output](./Pic27.png)

### Answer

    document.querySelector('.HotDealsAll__Heading__2fIbe').style.fontSize = '80px'

15. Webiste Name: [Dell](https://www.dell.com/en-in/shop/deals/laptop-deals?gacd=10415953-9016-5761040-285981356-0&dgc=ST&gclid=Cj0KCQjwguGYBhDRARIsAHgRm4-XUDMhhVNyHXb3s1gY4ZBzORr_d9Se-buhJwy7asyUe7YdqEA11eEaAt6UEALw_wcB&gclsrc=aw.ds&nclid=BxjBlpBQsX6pjSHh-L8YYSU77EpfXRkG1AGMB5Wbeu386ykspfrPDnfx_DdFau20)

### Topics

      querySelector,style.textAlign

### Sample Image

![Sample One](./Pic28.png)

### Tasks

       Convert the text “G15 Gaming Laptop” from left to right

### Output

![Output](./Pic29.png)

### Answer

    document.querySelector('.ps-title').style.textAlign = 'right'

16. Webiste Name: [Vercel](https://vercel.com/)

### Topics

     querySelector,innerHTMl

### Sample Image

![Sample One](./Pic30.png)

### Tasks

      change the heading “Start with the developer” to “Start with Scratch”

### Output

![Output](./Pic31.png)

### Answer

    document.querySelector('.section-title_title__VEDfK span').innerHTML = 'Start with Scratch'

17. Webiste Name: [Sony](https://www.sony.co.in/)

### Topics

    querySelector,innerHTMl

### Sample Image

![Sample One](./Pic33.png)

### Tasks

     change the button text To current Date.

### Output

![Output](./Pic32.png)

### Answer

    document.querySelector('.buy ').innerHTML = new Date();

18. Webiste Name: [Philips](https://www.philips.co.in/)

### Topics

     querySelector,style,backgroundcolor

### Sample Image

![Sample One](./Pic34.png)

### Tasks

    change the background colour blue to orange

### Output
    
![Output](./Pic35.png)

### Answer

    document.querySelector('.footerpage  .p-footer ').style.backgroundColor = 'Orange'


19. Webiste Name: [Canon](https://in.canon/)

### Topics

          querySelector,src

### Sample Image

![Sample One](./Pic36.png)

### Tasks

    extract the canon logo

### Output

![Output](./Pic37.png)

### Answer

    document.querySelector('.navbar-brand .logo').src

20. Webiste Name: [Oppo](https://www.oppo.com/in/)

### Topics

          querySelector,style,color

### Sample Image

![Sample One](./Pic38.png)

### Tasks

      Change the description colour black to orange

### Output

![Output](./Pic39.png)

### Answer

    document.querySelector('.desc').style.color = 'Orange'
