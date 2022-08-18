

![image](https://user-images.githubusercontent.com/34571056/185396634-a3115f2b-1a93-4223-961c-512170673c2a.png)


Behenlang is a toy programming langauge inspired from Bhailang.

## Geting Started


### Prerequisites

You need llvmlite and sly modules to run the project.
* llvmlite
  ```sh
  pip install llvmlite
  ```

* sly
  ```sh
  pip install sly
  ```

## Usage

### Compiling the code

Extention for behenlang is .behen , to compile .behen files use
```sh
python run.py <filename.behen>
```

This will generate a .ll intermediate code file in the same folder where code is present and output the result too.


### Documentation:

#### General

<code>kaam</code> is used to define a function. One must define <code>main</code> function in the project. Example :
```sh
kaam int main() {
    # code goes here
    behen bhejo 0     #similar to return
}
```

<code>behen</code> or <code>didi</code> is used to initialize any statement.

#### Print

<code>behen bolo(<strings here>)</code> or <code>didi bolo(<strings here>)</code> is used to print the strings :
```sh
kaam int main() {

    didi bolo("Namste Duniya \n")
    behen bolo("Hello World")       #this is comment

    behen bhejo 0
}
```
  
#### Defining Variables

```sh
kaam int main() {

    behen x=5
    behen y=9.0
    
    behen bhejo 0
}
```

#### Conditional Statements

```sh
kaam int main() {

    behen num1 = 18
    behen rem = num1 % 2
    behen agar rem == 0{
        behen bolo('Even')
    } 
    warna{
        behen bolo('Odd')
    }

    behen bhejo 0
}

```
  
#### Iterations

```sh
kaam int main(){
    behen i = 0
    jabtak i < 10
    {
        didi bolo('Hello ')
        didi i = i+1
    }
   didi bhejo 0
    }

```
                 
#### Calling Functions

```sh
kaam int hello() {
    behen bolo("Ye hai hello function\n")
    behen bhejo 0
}

kaam int main(){
    hello()
    behen bolo("Ye hai main fun")
    behen bhejo 0
}

```




## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Dont forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Sources:

1. https://school.geekwall.in/p/Byz8Rg0GX
2. https://llvmlite.readthedocs.io/en/latest/
3. https://sly.readthedocs.io/en/latest/sly.html
4. https://groups.seas.harvard.edu/courses/cs153/2019fa/llvmlite.html
5. https://buildmedia.readthedocs.org/media/pdf/llvmlite/latest/llvmlite.pdf



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
