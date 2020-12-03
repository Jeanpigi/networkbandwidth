<style>
    .header {
        width: 100vw;
        background-color: #24292e;
        color: #fafafafa;
    }

    .header-container {
        display: grid;
        grid-template-columns: 1fr 1fr;
    }
    .header-logo {
        display: flex;
        align-items: center;
        color: #fafafafa;
    }

    .header-logo picture img {
        width: 10rem;
    }

    .header-logo img {
        width: 70px;
        cursor: pointer;
    }

    .header-social {
        display: flex;
        justify-content: flex-end;
        align-items: center;
        margin-right: 1rem;
    }

    .header-social ul {
        display: flex;
    }

    .header-social li {
        padding-left: 1rem;
    }
    .header-social img {
        width: 20px;
    }
</style>

<header class="header">
    <div class="header-container">
        <a href="/#" class="header-logo">
            <picture>
                <img
                    src="https://i.ibb.co/rdF0Bhy/logo.png"
                    alt="logo"
                    border="0" />
            </picture>
            <h1>JbearP</h1>
        </a>

        <div class="header-social">
            <ul>
                <li>
                    <a
                        href="https://github.com/Jeanpigi"
                        target="_blank"
                        rel="noreferrer">
                        <img
                            src="https://i.ibb.co/vdBN8K9/github-icon.png"
                            alt="Github"
                            border="0" />
                    </a>
                </li>
                <li>
                    <a
                        href="https://www.instagram.com/jean_pierre_giovanni/"
                        target="_blank"
                        rel="noreferrer">
                        <img
                            src="https://i.ibb.co/5vbhJtk/instagram-icon.png"
                            alt="Instagram"
                            border="0" />
                    </a>
                </li>
                <li>
                    <a
                        href="https://www.facebook.com/JePiGi/"
                        target="_blank"
                        rel="noreferrer">
                        <img
                            src="https://i.ibb.co/DfGshZS/facebook-icon.png"
                            alt="Facebook"
                            border="0" />
                    </a>
                </li>
            </ul>
        </div>
    </div>
</header>
