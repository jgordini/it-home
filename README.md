# it-home

[Homepage](https://www.uab.edu/it/home/)

**CSS Changes**

body.linear #banner::after {
    content: "";
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    z-index: -100;
    background: #295135;
    mix-blend-mode: multiply;
    opacity: .9;
}

body.linear #whitebox {
    overflow: visible;
    margin: 6.4rem auto;
    max-width: 1280px;
    background: none;
}

body.linear [id=whitebox] .moduletable.alert:last-child {
    margin-bottom: 6.4rem;
}

body.linear [id=whitebox] .section {
    margin: 6.4rem 0;
}





