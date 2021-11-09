.site-footer {
background-color: black;
background-image: url('https://i.imgur.com/CEYEZp8.jpeg');
padding-bottom: 6.5em;
padding-top: 10.5em;
color: white !important;
border:4px solid black;
}

#colophon {
a:not(.button) {
color: inherit;

        &:hover,
        &:focus {
            color: $color-primary;
        }
    }

}

.site-info,
.social-links {
-ms-flex-align: center;
align-items: center;
display: -ms-flexbox;
display: flex;
-ms-flex-wrap: wrap;
flex-wrap: wrap;
-ms-flex-pack: center;
justify-content: center;
font-size: 0.675em;
line-height: 1.2;

    .button:not(.button-icon) {
        font-size: inherit;
        line-height: 1.2;
        padding: 0.3em 1em;
    }

}

.site-info {
margin: 0.25em 0 0;
text-align: center;

    .copyright,
    > a {
        margin: 0 4px 0.2em 0;
    }

}

.social-links {
margin-top: 0.5375em;

    a {
        margin: 0 50px 0.2em;
    }

    .icon {
        font-size: 20px;
        color:rgb(0, 0, 0);
        background-color: rgb(0, 0, 0);
    }

}

@media only screen and (min-width: 641px) {
.site-footer-inside {
-ms-flex-align: start;
align-items: flex-start;
display: -ms-flexbox;
display: flex;
}

    .site-info {
        -ms-flex-pack: start;
        justify-content: flex-start;
        text-align: left;
    }

    .social-links {
        -ms-flex: 0 0 auto;
        flex: 0 0 auto;
        -ms-flex-wrap: nowrap;
        flex-wrap: nowrap;
        -ms-flex-pack: start;
        justify-content: flex-start;
        margin-left: auto;
        margin-top: 0;

        a {
            margin-left: 20px;
            margin-right: 0;
        }
    }

}