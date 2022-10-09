## rsschool-cv

# Olesia Trebina

### Contacts:

- Discord: @Cranky#2826
- E-mail: olesyatrebina@gmail.com
- Telegram: @olesiatrebina
- Github: @olesiatr

### About myself

I am learning to become a Full Stack Developer. Coming to my skills - I know HTML (basics and semantics),CSS (basics, flexbox, adaptive and mobile-first css, BEM, SASS) and learning JavaScript at the moment. I did one successful team project and several solo projects.

I’m interested in Software Development because it has project-based structure, which can bring a whole new set of challenges. Also it can boost my problem-solving skills, it provides endless possibilities for professional growth. And I am excited to learn much more about this industry from professionals.

### Code example:

> const refs = {
> start: document.querySelector('button[data-start]'),
> stop: document.querySelector('button[data-stop]'),
> body: document.querySelector('body'),
> };
>
> let timerID = null;
>
> refs.start.addEventListener('click', onStartBtn);
> refs.stop.addEventListener('click', onStopBtn);
>
> function onStartBtn(e) {
>
> > > // Disables a start btn, while function is running
> > > e.target.disabled = true;
>
> > if (e.target.disabled) {
> >
> > // Changes the <body> background color
> > timerID = setInterval(() => {
> > refs.body.style.backgroundColor = getRandomHexColor();
> > }, 1000);
> > }
> > }
>
> function onStopBtn() {
>
> > // Activates a start btn
> > refs.start.disabled = false;
> > // Clears a timer
> > clearInterval(timerID);
> > }
>
> function getRandomHexColor() {
>
> > // Generates a random color
> > return `#${Math.floor(Math.random() * 16777215).toString(16)} `;
> > }

### Courses:

1. **GoIT** Full Stack Developer courses (_ongoing_)
2. **SheCodes** [Basics](https://www.shecodes.io/certificates/969ee2246449988ba49a5c7a87a00534), [Plus](https://www.shecodes.io/certificates/13867a2a6a15bf268260e0bf23cfcd35), [Responsive](https://www.shecodes.io/certificates/482a7637bebb87d5135b3476e4325680), React (_ongoing_)
3. **The Rolling Scopes School** JS/Frontend development course (_ongoing_)
4. **CS50**'s Introduction to Computer Science (_ongoing_)

### Education:

> **The National Law Academy of Ukraine named after Yaroslav the Wise**
>
> > 2018-2023 PhD. Postgraduate, International Law
>
> > 2008-2015 M. Sc. Law. Lawyer

### Language:

- **English**
  Upper-intermediate
- **Ukrainian**
  Native
- **Russian**
  Native
