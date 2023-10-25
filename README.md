}
.checkbox {
    margin: 20px 0;
}
.enviar {
    width: 40%;
    padding: 15px 0;
    background-color: #e54516;
    color: white;
    font-weight: bold;
    font-size: 18px;
    border: 1px solid transparent;
    border-radius: 30px;
    cursor: pointer;
    font-family: 'Montserrat', sans-serif;
}
.enviar:hover {
    transition: 0.5s;
    background-color: #781500;
    transform: scale(1.1);
}
table {
    background-color: white;
    margin: 2rem auto;
    box-shadow: 5px 10px 5px #988b7b;
    width: 940px;
}
thead {
    background-color: #009ccf;
    font-size: 20px;
    font-weight: bold;
    color: white;
}
th, td {
    border: 1px solid black;
    padding: 10px 20px;
    text-align: center;
}
footer {
    text-align: center;
    background-image: url(../img/bg.jpg);
    padding: 15px 0px;
}
.redes a {
    margin: 0 10px;
    text-decoration: none;
}
.redes img:hover {
    transition: 0.5s;
    transform: scale(1.1);
    opacity: 60%;
}
.copyright {
    font-size: 13px;
    color: white;
    margin-top: 15px;
}
/* Media queries */
@media screen and (max-width: 825px) {
    body {
        font-size: 16px;
    }
    .cabecalho, .principal, .mapa, .conteudo-beneficios, .video, 
    .produtos, form {
        width: auto;
    }
    /* Header */
    header {
        padding: 5px 0;
    }
    .cabecalho {
        text-align: center;
    }
    nav {
        position: static;
    }
    nav a {
        font-size: 20px;
    }
    nav a:active {
        color: #e54516;
        text-decoration: underline;
    }
    /* Home */
    .principal {
        padding: 1rem 0;
        margin: auto 1rem;
    }
    .titulo-principal {
        font-size: 20px;
    }
    #utensilios {
        width: 100px;
        height: 100px;
        margin: 0 1rem;
        box-shadow: 3px 3px 3px #781500;
    }
    #missao {
        font-size: 18px;
    }
    .localizacao {
        margin: 1rem;
        padding: 0;
    }
    .beneficios {
        text-align: center;
        padding: 1rem 0;
        margin: 1rem;
    }
    .lista-beneficios {
        width: 100%;
        margin-bottom: 1rem;
    }
    #imagem-beneficios {
        width: 100%;
        opacity: 100%;
        box-shadow: 6px 8px 4px #781500;
    }
    /* Produtos */
    .produtos {
        text-align: center;
    }
    .produtos li {
        display: inline-block;
        width: 75%;
        margin: 1rem 2rem;
    }
    .produtos-descricao {
        font-size: 18px;
    }
    /* Contato */
    form {
        margin: 0 20px;
    }
    form p {
        font-size: 12px;
    }
    form label, form legend {
        font-size: 16px;
    }
    .input-padrao {
        padding: 5px 10px;
        width: 80%;
    }
    textarea {
        padding: 5px 10px;
        width: 85%;
    }
    select {
        width: 30%;
    }
    .enviar {
        width: 60%;
    }
    table {
        margin: 20px;
        width: 70%;
    }
    thead {
        font-size: 16px;
    }
    th, td {
        font-size: 14px;
        padding: 7px 14px;
    }
}
