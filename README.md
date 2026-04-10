@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&family=Poppins:wght@400;600;700&display=swap');

body {
    font-family: 'Poppins', sans-serif;
    margin: 0;
    padding: 0;
    background: #FFFFFF;
    color: #1B365D;
    line-height: 1.7;
    min-height: 100vh;
    overflow-x: hidden;
}
header {
    background: #f8f9fa;
    color: #1B365D;
    padding: 70px 20px;
    text-align: center;
    border-bottom: 1px solid #e9ecef;
    box-shadow: 0 10px 24px rgba(27, 54, 93, 0.08);
    position: relative;
    border-radius: 0 0 40px 40px;
}
header::before {
    display: none;
}
header img {
    width: 120px;
    height: auto;
    margin-bottom: 18px;
    border-radius: 18px;
    box-shadow: 0 12px 30px rgba(27, 54, 93, 0.12);
    position: relative;
    z-index: 1;
}
header p {
    font-family: 'Montserrat', sans-serif;
    font-size: 1.2em;
    margin-top: 15px;
    font-weight: 600;
    letter-spacing: 0.25px;
    position: relative;
    z-index: 1;
    color: #1B365D;
    max-width: 760px;
    margin-left: auto;
    margin-right: auto;
    line-height: 1.8;
}
nav {
    background: linear-gradient(90deg, #FFD700 0%, #D4AF37 50%, #FFD700 100%);
    padding: 20px;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0,0,0,0.3);
    position: relative;
}
nav a {
    color: #1B365D;
    margin: 0 25px;
    text-decoration: none;
    font-weight: 600;
    font-size: 1.1em;
    transition: all 0.4s cubic-bezier(0.25, 0.46, 0.45, 0.94);
    padding: 10px 15px;
    border-radius: 25px;
}
nav a:hover {
    transform: translateY(-3px) scale(1.05);
    box-shadow: 0 6px 12px rgba(0,0,0,0.4);
}
section {
    padding: 80px 40px;
    margin: 40px auto;
    max-width: 1200px;
    background: #FFFFFF;
    border-radius: 20px;
    margin-bottom: 40px;
    box-shadow: 0 12px 24px rgba(27, 54, 93, 0.1);
    backdrop-filter: blur(20px);
    border: 2px solid #FFD700;
    position: relative;
}
section::after {
    content: '';
    position: absolute;
    top: -5px;
    left: -5px;
    right: -5px;
    bottom: -5px;
    background: linear-gradient(45deg, #FFD700, #D4AF37, #FFD700);
    border-radius: 25px;
    z-index: -1;
    opacity: 0.1;
}
}
section h2 {
    color: #FFD700;
    text-align: center;
    margin-bottom: 50px;
    font-size: 2.8em;
    font-family: 'Montserrat', sans-serif;
    font-weight: 700;
    text-shadow: 3px 3px 6px rgba(0,0,0,0.6);
    letter-spacing: 1px;
    font-style: italic;
}
.home-content {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 40px;
    max-width: 1200px;
    margin: 0 auto;
}
.home-text {
    flex: 1;
    text-align: left;
}
.home-text h2 {
    text-align: left;
    margin-bottom: 30px;
}
.home-text p {
    font-size: 1.2em;
    line-height: 1.6;
    margin-bottom: 40px;
}
.home-image {
    flex: 1;
    text-align: center;
}
.hero-image {
    max-width: 100%;
    height: auto;
    border-radius: 15px;
    box-shadow: 0 8px 16px rgba(0,0,0,0.3);
    transition: transform 0.3s ease;
}
.hero-image:hover {
    transform: scale(1.05);
}
.btn {
    background: linear-gradient(45deg, #FFD700 0%, #D4AF37 100%);
    color: #1B365D;
    padding: 18px 35px;
    text-decoration: none;
    border-radius: 50px;
    display: inline-block;
    font-weight: 600;
    font-size: 1.2em;
    transition: all 0.4s cubic-bezier(0.25, 0.46, 0.45, 0.94);
    box-shadow: 0 6px 12px rgba(0,0,0,0.4);
    border: 2px solid #FFD700;
    position: relative;
    overflow: hidden;
}
.btn::before {
    content: '';
    position: absolute;
    top: 0;
    left: -100%;
    width: 100%;
    height: 100%;
    background: linear-gradient(90deg, transparent, rgba(255,255,255,0.3), transparent);
    transition: left 0.6s ease;
}
.btn:hover::before {
    left: 100%;
}
.btn:hover {
    transform: translateY(-2px) scale(1.08);
    box-shadow: 0 8px 16px rgba(0,0,0,0.5);
}
ul {
    list-style-type: none;
    padding: 0;
}
ul li {
    background: linear-gradient(90deg, rgba(32, 178, 170, 0.05) 0%, rgba(32, 178, 170, 0.1) 100%);
    margin: 20px 0;
    padding: 25px;
    border-left: 6px solid #20B2AA;
    border-radius: 15px;
    box-shadow: 0 4px 8px rgba(27, 54, 93, 0.1);
    transition: all 0.3s cubic-bezier(0.25, 0.46, 0.45, 0.94);
    position: relative;
}
ul li::before {
    content: '';
    position: absolute;
    top: 10px;
    left: 10px;
    width: 20px;
    height: 20px;
    background: #20B2AA;
    border-radius: 50%;
    z-index: 1;
}
ul li:hover {
    transform: translateX(10px) rotate(1deg);
    box-shadow: 0 6px 12px rgba(0,0,0,0.4);
}
footer {
    background: #f8f9fa;
    color: #495057;
    text-align: center;
    padding: 80px 40px;
    margin-top: 60px;
    border-top: 1px solid #e9ecef;
    position: relative;
}
.footer-content .footer-logo {
    width: 120px;
    height: auto;
    margin-bottom: 20px;
    display: block;
    margin-left: auto;
    margin-right: auto;
}
.footer-content .tagline {
    font-family: 'Poppins', sans-serif;
    font-size: 1.2em;
    font-style: italic;
    color: #6c757d;
    line-height: 1.6;
    margin-bottom: 40px;
    max-width: 600px;
    margin-left: auto;
    margin-right: auto;
}
.footer-content .copyright {
    font-family: 'Poppins', sans-serif;
    font-size: 0.9em;
    color: #adb5bd;
    margin-top: 20px;
}
.about-text {
    text-align: justify;
    max-width: 1100px;
    margin: 0 auto;
    line-height: 1.9;
    position: relative;
    z-index: 1;
}
.about-text h1 {
    color: #1B365D;
    font-size: 2.5em;
    font-family: 'Montserrat', sans-serif;
    font-weight: 700;
    text-align: center;
    margin-bottom: 30px;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
    letter-spacing: 1px;
}
.about-header {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-bottom: 40px;
}
.about-logo {
    width: 150px;
    height: auto;
    margin-bottom: 20px;
    border-radius: 50%;
    box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    transition: transform 0.3s ease;
}
.about-logo:hover {
    transform: scale(1.1);
}
.about-text h3 {
    color: #FFFFFF;
    background: linear-gradient(135deg, #1B365D 0%, #20B2AA 100%);
    margin-top: 40px;
    font-size: 1.8em;
    font-family: 'Montserrat', sans-serif;
    font-weight: 700;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
    padding: 20px 30px;
    border-left: 6px solid #FFD700;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(27, 54, 93, 0.3);
}
.about-text ul {
    text-align: left;
}
.about-text ol {
    text-align: left;
    margin-left: 20px;
}
/* Responsive Design */
@media (max-width: 768px) {
    header h1 {
        font-size: 2.5em;
    }
    header p {
        font-size: 1.1em;
    }
    nav a {
        margin: 0 10px;
        font-size: 1em;
    }
    section {
        padding: 60px 20px;
    }
    section h2 {
        font-size: 2.2em;
    }
    .btn {
        padding: 15px 25px;
        font-size: 1.1em;
    }
    footer {
        padding: 60px 20px;
    }
    .footer-logo {
        width: 100px;
    }
    .footer-content .tagline {
        font-size: 1em;
    }
    .about-text h1 {
        font-size: 2em;
    }
    .about-logo {
        width: 120px;
    }
    .home-content {
        flex-direction: column;
        text-align: center;
    }
    .home-text h2 {
        text-align: center;
    }
}@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&family=Poppins:wght@400;600;700&display=swap');

body {
    font-family: 'Poppins', sans-serif;
    margin: 0;
    padding: 0;
    background: #FFFFFF;
    color: #1B365D;
    line-height: 1.7;
    min-height: 100vh;
    overflow-x: hidden;
}
header {
    background: #f8f9fa;
    color: #1B365D;
    padding: 70px 20px;
    text-align: center;
    border-bottom: 1px solid #e9ecef;
    box-shadow: 0 10px 24px rgba(27, 54, 93, 0.08);
    position: relative;
    border-radius: 0 0 40px 40px;
}
header::before {
    display: none;
}
header img {
    width: 120px;
    height: auto;
    margin-bottom: 18px;
    border-radius: 18px;
    box-shadow: 0 12px 30px rgba(27, 54, 93, 0.12);
    position: relative;
    z-index: 1;
}
header p {
    font-family: 'Montserrat', sans-serif;
    font-size: 1.2em;
    margin-top: 15px;
    font-weight: 600;
    letter-spacing: 0.25px;
    position: relative;
    z-index: 1;
    color: #1B365D;
    max-width: 760px;
    margin-left: auto;
    margin-right: auto;
    line-height: 1.8;
}
nav {
    background: linear-gradient(90deg, #FFD700 0%, #D4AF37 50%, #FFD700 100%);
    padding: 20px;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0,0,0,0.3);
    position: relative;
}
nav a {
    color: #1B365D;
    margin: 0 25px;
    text-decoration: none;
    font-weight: 600;
    font-size: 1.1em;
    transition: all 0.4s cubic-bezier(0.25, 0.46, 0.45, 0.94);
    padding: 10px 15px;
    border-radius: 25px;
}
nav a:hover {
    transform: translateY(-3px) scale(1.05);
    box-shadow: 0 6px 12px rgba(0,0,0,0.4);
}
section {
    padding: 80px 40px;
    margin: 40px auto;
    max-width: 1200px;
    background: #FFFFFF;
    border-radius: 20px;
    margin-bottom: 40px;
    box-shadow: 0 12px 24px rgba(27, 54, 93, 0.1);
    backdrop-filter: blur(20px);
    border: 2px solid #FFD700;
    position: relative;
}
section::after {
    content: '';
    position: absolute;
    top: -5px;
    left: -5px;
    right: -5px;
    bottom: -5px;
    background: linear-gradient(45deg, #FFD700, #D4AF37, #FFD700);
    border-radius: 25px;
    z-index: -1;
    opacity: 0.1;
}
}
section h2 {
    color: #FFD700;
    text-align: center;
    margin-bottom: 50px;
    font-size: 2.8em;
    font-family: 'Montserrat', sans-serif;
    font-weight: 700;
    text-shadow: 3px 3px 6px rgba(0,0,0,0.6);
    letter-spacing: 1px;
    font-style: italic;
}
.home-content {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 40px;
    max-width: 1200px;
    margin: 0 auto;
}
.home-text {
    flex: 1;
    text-align: left;
}
.home-text h2 {
    text-align: left;
    margin-bottom: 30px;
}
.home-text p {
    font-size: 1.2em;
    line-height: 1.6;
    margin-bottom: 40px;
}
.home-image {
    flex: 1;
    text-align: center;
}
.hero-image {
    max-width: 100%;
    height: auto;
    border-radius: 15px;
    box-shadow: 0 8px 16px rgba(0,0,0,0.3);
    transition: transform 0.3s ease;
}
.hero-image:hover {
    transform: scale(1.05);
}
.btn {
    background: linear-gradient(45deg, #FFD700 0%, #D4AF37 100%);
    color: #1B365D;
    padding: 18px 35px;
    text-decoration: none;
    border-radius: 50px;
    display: inline-block;
    font-weight: 600;
    font-size: 1.2em;
    transition: all 0.4s cubic-bezier(0.25, 0.46, 0.45, 0.94);
    box-shadow: 0 6px 12px rgba(0,0,0,0.4);
    border: 2px solid #FFD700;
    position: relative;
    overflow: hidden;
}
.btn::before {
    content: '';
    position: absolute;
    top: 0;
    left: -100%;
    width: 100%;
    height: 100%;
    background: linear-gradient(90deg, transparent, rgba(255,255,255,0.3), transparent);
    transition: left 0.6s ease;
}
.btn:hover::before {
    left: 100%;
}
.btn:hover {
    transform: translateY(-2px) scale(1.08);
    box-shadow: 0 8px 16px rgba(0,0,0,0.5);
}
ul {
    list-style-type: none;
    padding: 0;
}
ul li {
    background: linear-gradient(90deg, rgba(32, 178, 170, 0.05) 0%, rgba(32, 178, 170, 0.1) 100%);
    margin: 20px 0;
    padding: 25px;
    border-left: 6px solid #20B2AA;
    border-radius: 15px;
    box-shadow: 0 4px 8px rgba(27, 54, 93, 0.1);
    transition: all 0.3s cubic-bezier(0.25, 0.46, 0.45, 0.94);
    position: relative;
}
ul li::before {
    content: '';
    position: absolute;
    top: 10px;
    left: 10px;
    width: 20px;
    height: 20px;
    background: #20B2AA;
    border-radius: 50%;
    z-index: 1;
}
ul li:hover {
    transform: translateX(10px) rotate(1deg);
    box-shadow: 0 6px 12px rgba(0,0,0,0.4);
}
footer {
    background: #f8f9fa;
    color: #495057;
    text-align: center;
    padding: 80px 40px;
    margin-top: 60px;
    border-top: 1px solid #e9ecef;
    position: relative;
}
.footer-content .footer-logo {
    width: 120px;
    height: auto;
    margin-bottom: 20px;
    display: block;
    margin-left: auto;
    margin-right: auto;
}
.footer-content .tagline {
    font-family: 'Poppins', sans-serif;
    font-size: 1.2em;
    font-style: italic;
    color: #6c757d;
    line-height: 1.6;
    margin-bottom: 40px;
    max-width: 600px;
    margin-left: auto;
    margin-right: auto;
}
.footer-content .copyright {
    font-family: 'Poppins', sans-serif;
    font-size: 0.9em;
    color: #adb5bd;
    margin-top: 20px;
}
.about-text {
    text-align: justify;
    max-width: 1100px;
    margin: 0 auto;
    line-height: 1.9;
    position: relative;
    z-index: 1;
}
.about-text h1 {
    color: #1B365D;
    font-size: 2.5em;
    font-family: 'Montserrat', sans-serif;
    font-weight: 700;
    text-align: center;
    margin-bottom: 30px;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
    letter-spacing: 1px;
}
.about-header {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-bottom: 40px;
}
.about-logo {
    width: 150px;
    height: auto;
    margin-bottom: 20px;
    border-radius: 50%;
    box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    transition: transform 0.3s ease;
}
.about-logo:hover {
    transform: scale(1.1);
}
.about-text h3 {
    color: #FFFFFF;
    background: linear-gradient(135deg, #1B365D 0%, #20B2AA 100%);
    margin-top: 40px;
    font-size: 1.8em;
    font-family: 'Montserrat', sans-serif;
    font-weight: 700;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
    padding: 20px 30px;
    border-left: 6px solid #FFD700;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(27, 54, 93, 0.3);
}
.about-text ul {
    text-align: left;
}
.about-text ol {
    text-align: left;
    margin-left: 20px;
}
/* Responsive Design */
@media (max-width: 768px) {
    header h1 {
        font-size: 2.5em;
    }
    header p {
        font-size: 1.1em;
    }
    nav a {
        margin: 0 10px;
        font-size: 1em;
    }
    section {
        padding: 60px 20px;
    }
    section h2 {
        font-size: 2.2em;
    }
    .btn {
        padding: 15px 25px;
        font-size: 1.1em;
    }
    footer {
        padding: 60px 20px;
    }
    .footer-logo {
        width: 100px;
    }
    .footer-content .tagline {
        font-size: 1em;
    }
    .about-text h1 {
        font-size: 2em;
    }
    .about-logo {
        width: 120px;
    }
    .home-content {
        flex-direction: column;
        text-align: center;
    }
    .home-text h2 {
        text-align: center;
    }
}
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&family=Poppins:wght@400;600;700&display=swap');

body {
    font-family: 'Poppins', sans-serif;
    margin: 0;
    padding: 0;
    background: #FFFFFF;
    color: #1B365D;
    line-height: 1.7;
    min-height: 100vh;
    overflow-x: hidden;
}
header {
    background: #f8f9fa;
    color: #1B365D;
    padding: 70px 20px;
    text-align: center;
    border-bottom: 1px solid #e9ecef;
    box-shadow: 0 10px 24px rgba(27, 54, 93, 0.08);
    position: relative;
    border-radius: 0 0 40px 40px;
}
header::before {
    display: none;
}
header img {
    width: 120px;
    height: auto;
    margin-bottom: 18px;
    border-radius: 18px;
    box-shadow: 0 12px 30px rgba(27, 54, 93, 0.12);
    position: relative;
    z-index: 1;
}
header p {
    font-family: 'Montserrat', sans-serif;
    font-size: 1.2em;
    margin-top: 15px;
    font-weight: 600;
    letter-spacing: 0.25px;
    position: relative;
    z-index: 1;
    color: #1B365D;
    max-width: 760px;
    margin-left: auto;
    margin-right: auto;
    line-height: 1.8;
}
nav {
    background: linear-gradient(90deg, #FFD700 0%, #D4AF37 50%, #FFD700 100%);
    padding: 20px;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0,0,0,0.3);
    position: relative;
}
nav a {
    color: #1B365D;
    margin: 0 25px;
    text-decoration: none;
    font-weight: 600;
    font-size: 1.1em;
    transition: all 0.4s cubic-bezier(0.25, 0.46, 0.45, 0.94);
    padding: 10px 15px;
    border-radius: 25px;
}
nav a:hover {
    transform: translateY(-3px) scale(1.05);
    box-shadow: 0 6px 12px rgba(0,0,0,0.4);
}
section {
    padding: 80px 40px;
    margin: 40px auto;
    max-width: 1200px;
    background: #FFFFFF;
    border-radius: 20px;
    margin-bottom: 40px;
    box-shadow: 0 12px 24px rgba(27, 54, 93, 0.1);
    backdrop-filter: blur(20px);
    border: 2px solid #FFD700;
    position: relative;
}
section::after {
    content: '';
    position: absolute;
    top: -5px;
    left: -5px;
    right: -5px;
    bottom: -5px;
    background: linear-gradient(45deg, #FFD700, #D4AF37, #FFD700);
    border-radius: 25px;
    z-index: -1;
    opacity: 0.1;
}
}
section h2 {
    color: #FFD700;
    text-align: center;
    margin-bottom: 50px;
    font-size: 2.8em;
    font-family: 'Montserrat', sans-serif;
    font-weight: 700;
    text-shadow: 3px 3px 6px rgba(0,0,0,0.6);
    letter-spacing: 1px;
    font-style: italic;
}
.home-content {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 40px;
    max-width: 1200px;
    margin: 0 auto;
}
.home-text {
    flex: 1;
    text-align: left;
}
.home-text h2 {
    text-align: left;
    margin-bottom: 30px;
}
.home-text p {
    font-size: 1.2em;
    line-height: 1.6;
    margin-bottom: 40px;
}
.home-image {
    flex: 1;
    text-align: center;
}
.hero-image {
    max-width: 100%;
    height: auto;
    border-radius: 15px;
    box-shadow: 0 8px 16px rgba(0,0,0,0.3);
    transition: transform 0.3s ease;
}
.hero-image:hover {
    transform: scale(1.05);
}
.btn {
    background: linear-gradient(45deg, #FFD700 0%, #D4AF37 100%);
    color: #1B365D;
    padding: 18px 35px;
    text-decoration: none;
    border-radius: 50px;
    display: inline-block;
    font-weight: 600;
    font-size: 1.2em;
    transition: all 0.4s cubic-bezier(0.25, 0.46, 0.45, 0.94);
    box-shadow: 0 6px 12px rgba(0,0,0,0.4);
    border: 2px solid #FFD700;
    position: relative;
    overflow: hidden;
}
.btn::before {
    content: '';
    position: absolute;
    top: 0;
    left: -100%;
    width: 100%;
    height: 100%;
    background: linear-gradient(90deg, transparent, rgba(255,255,255,0.3), transparent);
    transition: left 0.6s ease;
}
.btn:hover::before {
    left: 100%;
}
.btn:hover {
    transform: translateY(-2px) scale(1.08);
    box-shadow: 0 8px 16px rgba(0,0,0,0.5);
}
ul {
    list-style-type: none;
    padding: 0;
}
ul li {
    background: linear-gradient(90deg, rgba(32, 178, 170, 0.05) 0%, rgba(32, 178, 170, 0.1) 100%);
    margin: 20px 0;
    padding: 25px;
    border-left: 6px solid #20B2AA;
    border-radius: 15px;
    box-shadow: 0 4px 8px rgba(27, 54, 93, 0.1);
    transition: all 0.3s cubic-bezier(0.25, 0.46, 0.45, 0.94);
    position: relative;
}
ul li::before {
    content: '';
    position: absolute;
    top: 10px;
    left: 10px;
    width: 20px;
    height: 20px;
    background: #20B2AA;
    border-radius: 50%;
    z-index: 1;
}
ul li:hover {
    transform: translateX(10px) rotate(1deg);
    box-shadow: 0 6px 12px rgba(0,0,0,0.4);
}
footer {
    background: #f8f9fa;
    color: #495057;
    text-align: center;
    padding: 80px 40px;
    margin-top: 60px;
    border-top: 1px solid #e9ecef;
    position: relative;
}
.footer-content .footer-logo {
    width: 120px;
    height: auto;
    margin-bottom: 20px;
    display: block;
    margin-left: auto;
    margin-right: auto;
}
.footer-content .tagline {
    font-family: 'Poppins', sans-serif;
    font-size: 1.2em;
    font-style: italic;
    color: #6c757d;
    line-height: 1.6;
    margin-bottom: 40px;
    max-width: 600px;
    margin-left: auto;
    margin-right: auto;
}
.footer-content .copyright {
    font-family: 'Poppins', sans-serif;
    font-size: 0.9em;
    color: #adb5bd;
    margin-top: 20px;
}
.about-text {
    text-align: justify;
    max-width: 1100px;
    margin: 0 auto;
    line-height: 1.9;
    position: relative;
    z-index: 1;
}
.about-text h1 {
    color: #1B365D;
    font-size: 2.5em;
    font-family: 'Montserrat', sans-serif;
    font-weight: 700;
    text-align: center;
    margin-bottom: 30px;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
    letter-spacing: 1px;
}
.about-header {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-bottom: 40px;
}
.about-logo {
    width: 150px;
    height: auto;
    margin-bottom: 20px;
    border-radius: 50%;
    box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    transition: transform 0.3s ease;
}
.about-logo:hover {
    transform: scale(1.1);
}
.about-text h3 {
    color: #FFFFFF;
    background: linear-gradient(135deg, #1B365D 0%, #20B2AA 100%);
    margin-top: 40px;
    font-size: 1.8em;
    font-family: 'Montserrat', sans-serif;
    font-weight: 700;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
    padding: 20px 30px;
    border-left: 6px solid #FFD700;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(27, 54, 93, 0.3);
}
.about-text ul {
    text-align: left;
}
.about-text ol {
    text-align: left;
    margin-left: 20px;
}
/* Responsive Design */
@media (max-width: 768px) {
    header h1 {
        font-size: 2.5em;
    }
    header p {
        font-size: 1.1em;
    }
    nav a {
        margin: 0 10px;
        font-size: 1em;
    }
    section {
        padding: 60px 20px;
    }
    section h2 {
        font-size: 2.2em;
    }
    .btn {
        padding: 15px 25px;
        font-size: 1.1em;
    }
    footer {
        padding: 60px 20px;
    }
    .footer-logo {
        width: 100px;
    }
    .footer-content .tagline {
        font-size: 1em;
    }
    .about-text h1 {
        font-size: 2em;
    }
    .about-logo {
        width: 120px;
    }
    .home-content {
        flex-direction: column;
        text-align: center;
    }
    .home-text h2 {
        text-align: center;
    }
}<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Booking Konsultasi - RE-SOLUSI</title>
    <link rel="stylesheet" href="../css/style.css">
</head>
<body>
    <header>
        <img src="../images/resolusi.png" alt="Logo RE-SOLUSI">
        <p>Dari Jalan Buntu Menuju Jawaban Terpadu</p>
    </header>
    <nav>
        <a href="../index.html">Home</a>
        <a href="booking.html">Booking Konsultasi</a>
        <a href="panduan.html">Panduan Layanan</a>
        <a href="harga.html">Daftar Harga</a>
        <a href="about.html">About Us</a>
    </nav>

    <section>
        <h2>Booking Konsultasi</h2>
        <p>Jadwalkan konsultasi akademik Anda sekarang melalui WhatsApp untuk mendapatkan bimbingan berkualitas.</p>
        <a href="https://wa.me/6285802864517" class="btn">Booking via WhatsApp</a>
    </section>

    <footer>
        <div class="footer-content">
            <img src="../images/resolusi.png" alt="Re-Solusi" class="footer-logo">
            <p class="tagline">Temukan Jawaban di Setiap Hambatan.<br>Karena Setiap Riset Butuh Arah yang Tepat.</p>
            <p class="copyright">&copy; 2026 RE-SOLUSI. All rights reserved.</p>
        </div>
    </footer>

    <script src="../js/script.js"></script>
</body>
</html>
