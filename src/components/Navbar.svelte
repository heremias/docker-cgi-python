<style>

    ul {
        list-style-type: none;
        padding: 0;
        margin: 0;
        display: flex;
        padding-right: 7.5%;
    }

    a {
        text-decoration: none;
        display: block;
        padding: 10px 20px;
    }

    li > a:hover {
        text-decoration: underline;
    }

    header {
        z-index: 1;
        background-color: #040815;
        display: flex;
        align-items: center;
        box-shadow: 0 1px #202020;
        padding: 2em 0 1.25em 0;
        min-width: 100%;
    }

    .logo {
        padding-left: 7.5%;
    }

    .logo a {
        font-size: 17px;
        color: #9CF1E2;
        display: flex;
        font-family: Antonio;
        align-items: center;
    } 

    .logo-img {
        padding-right: 7.5%;
    }

    .nav-items {
        padding-right: 7.5%;
    }

    .nav-items a {
        font-size: 20px;
        color: #FF8C68;
    }

    .nav-bar {
        min-width: max-content;
        display: flex;
        justify-content: space-between;
    }

</style>

<header class="nav-bar">
    <div class="logo">
        <a href="/#/">
            <svg width="40" height="40" class="logo-img" viewBox="0 0 45 45" fill="none" xmlns="http://www.w3.org/2000/svg">
                <rect width="45" height="45" rx="0.75" fill="#070E25"/>
                <rect width="15" height="15" rx="0.75" transform="matrix(0 -1 -1 0 15 45)" fill="#89D4C9"/>
                <rect width="16.8" height="16.8" rx="0.84" transform="matrix(0 -1 -1 0 30.9004 30.9)" fill="#89D4C9"/>
                <rect width="15" height="15" rx="0.75" transform="matrix(0 -1 -1 0 45 15)" fill="#89D4C9"/>
            </svg>
            InteGR8
        </a>
    </div>
    
    
    <ul class="nav-items">
        <li>
            <a href=/#>
                Home
            </a>
        </li>
        <li>
            <a href=/#/about>
                About
            </a>
        </li>
        <li>
            <a href="https://github.com/yogesh174/web-menu-backend/" class="github">
                <svg width="25" height="25" viewBox="0 0 45 45" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M22.5 0C10.0687 0 0 10.0688 0 22.5C0 32.4563 6.44062 40.8656 15.3844 43.8469C16.5094 44.0438 16.9312 43.3688 16.9312 42.7781C16.9312 42.2438 16.9031 40.4719 16.9031 38.5875C11.25 39.6281 9.7875 37.2094 9.3375 35.9438C9.08437 35.2969 7.9875 33.3 7.03125 32.7656C6.24375 32.3438 5.11875 31.3031 7.00312 31.275C8.775 31.2469 10.0406 32.9063 10.4625 33.5813C12.4875 36.9844 15.7219 36.0281 17.0156 35.4375C17.2125 33.975 17.8031 32.9906 18.45 32.4281C13.4438 31.8656 8.2125 29.925 8.2125 21.3188C8.2125 18.8719 9.08438 16.8469 10.5188 15.2719C10.2937 14.7094 9.50625 12.4031 10.7437 9.30938C10.7437 9.30938 12.6281 8.71875 16.9312 11.6156C18.7312 11.1094 20.6437 10.8563 22.5562 10.8563C24.4688 10.8563 26.3813 11.1094 28.1812 11.6156C32.4844 8.69063 34.3688 9.30938 34.3688 9.30938C35.6063 12.4031 34.8187 14.7094 34.5938 15.2719C36.0281 16.8469 36.9 18.8438 36.9 21.3188C36.9 29.9531 31.6406 31.8656 26.6344 32.4281C27.45 33.1313 28.1531 34.4813 28.1531 36.5906C28.1531 39.6 28.125 42.0188 28.125 42.7781C28.125 43.3688 28.5469 44.0719 29.6719 43.8469C34.1385 42.3389 38.0197 39.4682 40.7694 35.6388C43.519 31.8095 44.9987 27.2143 45 22.5C45 10.0688 34.9313 0 22.5 0Z" fill="#FF8C68"/>
                </svg>
            </a>
        </li>
    </ul> 
</header>