
:root{
  --gray: #F5F5F5;
  --purple: #3F2860;
  --green: #9BC1C2;
}

body{
  background-color: var(--gray);
  color: var(--purple);
  font-family: Verdana, Arial, sans-serif;
  margin: 0;
  line-height: 1.5;
}

header, main, footer{
  width: 80%;
  max-width: calc(1000px - 32px);
  margin: 0 auto;
  padding: 16px;
}

header{
  background-color: var(--green);
  text-align: center;
}

h1{
  margin: 8px 0;
}

nav{
  text-align: center;
  font-weight: bold;
  width: 100%;
  max-width: 600px;
  margin: 0 auto;
}

nav ul{
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  gap: 16px;
  list-style-type: none;
  padding: 0;
}

a{
  display: block;
  color: var(--purple);
}

a:hover{
  text-decoration: none;
}

nav a{
  text-decoration: none;
  padding: 16px;
  font-size: 1.25rem;
}

nav a:hover{
  background-color: var(--purple);
  color: var(--gray);
}

h2{
  text-align: center;
}

p, main ul, address{
  max-width: 65ch;
  margin: 16px auto;
}

.studio{
  font-style: italic;
  font-weight: 600;
}

footer{
  background-color: var(--green);
  font-style: italic;
  text-align: center;
}
