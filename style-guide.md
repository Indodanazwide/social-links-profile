:root {
    --green: hsl(75, 94%, 57%);
    --white: hsl(0, 0%, 100%);
    --grey-700: hsl(0, 0%, 20%);
    --grey-800: hsl(0, 0%, 12%);
    --grey-900: hsl(0, 0%, 8%);
  
    --font-family: 'Inter', sans-serif;
    --font-size-body: 14px;
    --font-size-footer: 10px;
    --font-weight-regular: 400;
    --font-weight-semibold: 600;
    --font-weight-bold: 700;
  
    --mobile-width: 375px;
    --desktop-width: 1440px;
}
  
* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

body, main, section {
    display: flex;
    justify-content: center;
    align-items: center;
}

body {
    background-color: var(--grey-900);
    font-size: var(--font-size-body);
    font-family: var(--font-family);
    max-width: var(--desktop-width);
    color: var(--white);
    min-height: 100vh;
}

main, ul li {
    border-radius: .7rem;
}

main {
    background-color: var(--grey-800);
    font-weight: var(--font-weight-semibold);
    flex-direction: column;
    min-height: 80vh;
    max-height: 95vh;
    min-width: 20vw;
    padding: 2rem;
}

h1 {
    margin: 1.2rem 0 1rem;
    font-weight: var(--font-weight-bold);
}

.header p {
    color: var(--green);
}

section {
    flex-direction: column;
}

img {
    width: 50%;
    height: auto;
    border-radius: 50%;
    object-fit: cover;
    transition: .5s;
    cursor: auto;
}

img:hover {
    transform: scale(1.1);
}

img:active {
    transform: scale(1.2);
}

.description {
    margin: 1.2rem 0;
    font-weight: var(--font-weight-regular);
}

ul {
    width: 100%
}

ul li {
    list-style: none;
    text-align: center;
    padding: 1rem 4rem;
    margin: 1rem 0;
    background-color: var(--grey-700);
    transition: .5s;
    cursor: pointer;
}

ul li:hover {
    background-color: var(--green);
}

ul li:active {
    background-color: var(--grey-700);
    transform: scale(1.1);
}

ul li a {
    display: block;
    width: 100%;
    height: 100%;
    color: var(--white);
    text-decoration: none;
}

.footer {
    margin-top: .5rem;
}

.footer p {
    text-align: center;
    line-height: 1.5;
    font-size: var(--font-size-footer);
}

.footer p a {
    color: var(--green); 
    font-weight: unset;
    text-decoration: none;
    transition: .5s;
}

.footer p a:hover {
    color: var(--white);
}

