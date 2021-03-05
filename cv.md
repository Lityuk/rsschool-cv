# Uladzimir Litsiuk

## Contact info:

#### Telephone number:
- +375295140771
- +375259932243
#### Skype:
- litik87
#### e-mail:
- lityuk@gmail.com
#### github:
- https://github.com/Lityuk

## Summary:

I am an communicative and responsible person. I'm a quick learner and a team player. My objective: looking for a career start as a front‐end developer with the future grow to full‐stack.  My English level is pre intermediate.

## Skills:

#### Programming Languages/ Technologies:

- HTML/HTML5
- CSS3
- JavaScript
#### Frameworks:

- Bootstrap

#### Development Tools:

- GIT
- Visual Studio Code
## Code:
```
let newUl = document.createElement('ul');
document.body.append(newUl);
newUl.innerHTML = '';

function listGenerator(parent) {
  let question = confirm('Вы хотите создать новый список');
  if (question) {
    let parrentElement = document.querySelector(parent);
    let newUl = document.createElement('ul');
    parrentElement.append(newUl);

    while (true) {
      let liElement = prompt('Введите элемент списка', '');
      if (!liElement) break;
      let newli = document.createElement('li');
      newli.textContent = liElement;
      newUl.append(newli);
    }
  } else alert('Ну и ладненько');
}

listGenerator('.list-wrap')
```
## Education:

- Belarusian National Technical University, Minsk, Belarus (2004-2009 )
  Specialist (Bachelor Degree) – Electrical power systems and nets ( Power Engineering )

## English level

Pre-Intermediate (A2)
