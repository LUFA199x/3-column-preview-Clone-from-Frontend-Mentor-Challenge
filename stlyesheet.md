# 3-column-preview-Clone-from-Frontend-Mentor-Challenge

* {
  margin: 0;
  padding: 0;
}

body {
  font-size: 15px;
}

main {
  color: #fff;
  max-width: 1440px;
  display: flex;
  justify-content: center;
  margin-top: 50px;
}

img {
  width: 25%;
  padding-left: 50px;
  padding-top: 45px;
  padding-bottom: 47px;
}

h1 {
  color: hsl(0, 0%, 95%);
  font-family: "Lucida Sans Unicode";
  padding-left: 50px;
  padding-bottom: 30px;
  letter-spacing: 1px;
  font-size: 40px;
}

p {
  color: hsla(0, 0%, 100%, 0.75);
  font-family: "Lexend Deca";
  padding-left: 50px;
  padding-right: 90px;
  padding-bottom: 50px;
  line-height: 25px;
}

button {
  border: none;
  font-family: "Lexend Deca";
  border-radius: 20px;
  background-color: hsl(0, 0%, 95%);
  width: 145px;
  height: 45px;
  margin: auto;
  margin-left: 50px;
}

footer {
  text-align: center;
}

.first-column {
  background-color: darkgoldenrod;
  display: flex;
  flex-direction: column;
  width: 350px;
  height: 550px;
  border-radius: 8px 0 0 8px;
}

.first-column button {
  color: darkgoldenrod;
}

.first-column button:hover {
  border: 2px solid hsl(0, 0%, 95%);
  color: hsl(0, 0%, 95%);
  background-color: darkgoldenrod;
}

.second-column {
  background-color: mediumvioletred;
  display: flex;
  flex-direction: column;
  width: 350px;
  height: 550px;
  border-radius: 8px 0 0 8px;
}

.second-column button {
  color: mediumvioletred;
}

.second-column button:hover {
  border: 2px solid hsl(0, 0%, 95%);
  color: hsl(0, 0%, 95%);
  background-color: mediumvioletred;
}

.third-column {
  background-color: darkseagreen;
  display: flex;
  flex-direction: column;
  width: 350px;
  height: 550px;
  border-radius: 8px 0 0 8px;
}

.third-column button {
  color: darkseagreen;
}

.third-column button:hover {
  border: 2px solid hsl(0, 0%, 95%);
  color: hsl(0, 0%, 95%);
  background-color: darkseagreen;
}

@media screen and (min-width: 375px) and (max-width: 425px) {
  main {
    max-width: 375px;
    flex-direction: column;
    margin-left: 1rem;
    margin-right: 1rem;
  }

  .first-column {
    border-radius: 0 0 8px 8px;
  }

  .third-column {
    border-radius: 0 0 8px 8px;
  }
}

@media screen and (min-width: 768px) and (max-width: 1023px) {
  p {
    padding-right: 60px;
  }
}
