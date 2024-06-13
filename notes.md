* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

body {
  background-color: #365e32;
}

.pageone {
  min-height: 100vh;
  width: 100%;
  overflow: hidden;
}

.header {
  display: flex;
  height: 17vh;
  width: 100%;
  align-items: center;
  padding: 4vw 2vw;
}

navbar {
  display: flex;
  align-items: center;
  justify-content: center;
}

img {
  height: 90px;
  width: auto;
  transition: all 1s ease-in-out;
}

navbar img:hover {
  cursor: pointer;
  scale: 2;
  transform: translate3d(15px, 15px, 15px);
}
navbar ul {
  display: flex;
  gap: 10px;
  align-items: center;
  justify-content: center;
  list-style: none;
  margin-left: 62vw;
}
navbar li {
  color: #e8e8e8;
  align-items: center;
  justify-content: center;
  margin-left: 10px;
  font-family: "Oswald";
  font-size: 1.3vw;
  font-weight: 300;
  font-style: normal;
  letter-spacing: 2px;
}

navbar li:hover {
  cursor: pointer;
  color: #e7d37f;
  scale: 1.1;
}

.hero-section {
  height: 80vh;
  width: 100%;
  display: flex;
  position: relative;
}

.hero {
  display: flex;
  position: absolute;
  left: 37vw;
}

.hero img {
  height: 43vw;
  z-index: 1;
}

.hero-heading {
  padding: 4vw;
}

.hero-heading span {
  font-size: 15vw;
  align-items: center;
  justify-content: center;
  letter-spacing: 15px;
  margin-left: 3.5vw;
  position: absolute;
  top: 0px;
}

.hero-heading h1 {
  width: 100%;
  font-size: 10.5vw;
  font-family: "Danfo";
  font-optical-sizing: auto;
  font-weight: 400;
  font-style: normal;
  font-variation-settings: "ELSH" 0;
  color: #e7d37f;
  letter-spacing: 4vw;
  padding: 0.7vw;
  align-items: center;
  justify-content: center;
}
