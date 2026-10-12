# bugema-university-
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="description" content="Bugema University: quality education, practical skills and Christian values.">
<title>Bugema University | Home</title>
<style>
  :root{--green:#0f4a2a;--green2:#176a3c;--gold:#d9a22b;--ink:#17201b;--muted:#5a665e;--paper:#f6f7f4;--white:#fff;--line:#dfe4dc}
  *{box-sizing:border-box;margin:0;padding:0}
  html{scroll-padding-top:90px}
  body{font-family:system-ui,-apple-system,"Segoe UI",Roboto,Arial,sans-serif;color:var(--ink);background:var(--paper);line-height:1.65}
  h1,h2,h3{font-family:Georgia,"Times New Roman",serif;line-height:1.2}
  a{color:inherit}
  .wrap{max-width:1080px;margin:auto;padding:0 20px}
  .topbar{background:var(--ink);color:#d5dcd7;font-size:.85rem}
  .topbar .wrap{display:flex;flex-wrap:wrap;justify-content:space-between;gap:6px 20px;padding-top:7px;padding-bottom:7px}
  header{background:var(--white);border-bottom:1px solid var(--line);position:sticky;top:0;z-index:10}
  header .wrap{display:flex;flex-wrap:wrap;align-items:center;justify-content:space-between;gap:10px;padding-top:12px;padding-bottom:12px}
  .brand{display:flex;align-items:center;gap:12px;text-decoration:none}
  .logo{width:44px;height:44px;border-radius:50%;background:var(--green);color:var(--gold);display:grid;place-items:center;font-family:Georgia,serif;font-weight:bold;border:2px solid var(--gold)}
  .brand b{display:block;font-family:Georgia,serif;font-size:1.1rem;color:var(--green)}
  .brand small{color:var(--muted);font-size:.78rem}
  nav{display:flex;flex-wrap:wrap;gap:4px 20px;align-items:center}
  nav a{text-decoration:none;font-size:.95rem;font-weight:500;padding:4px 0;border-bottom:2px solid transparent}
  nav a:hover{border-color:var(--gold)}
  nav a.cta{background:var(--green);color:#fff;padding:9px 18px;border-radius:5px;border:0}
  nav a.cta:hover{background:var(--green2)}
  .hero{background:linear-gradient(115deg,var(--green) 0%,#0b3a21 100%);color:#fff;padding:96px 0 88px}
  .hero h1{font-size:clamp(2.1rem,5.5vw,3.5rem);max-width:720px;margin-bottom:16px}
  .hero p{max-width:560px;font-size:1.1rem;color:#dbe8df;margin-bottom:28px}
  .btn{display:inline-block;padding:13px 26px;border-radius:5px;font-weight:600;text-decoration:none;margin:0 10px 10px 0}
  .btn.gold{background:var(--gold);color:var(--ink)}
  .btn.gold:hover{background:#e8b440}
  .btn.line{border:2px solid rgba(255,255,255,.7);color:#fff}
  .btn.line:hover{background:rgba(255,255,255,.1)}
  section{padding:72px 0}
  .alt{background:var(--white);border-top:1px solid var(--line);border-bottom:1px solid var(--line)}
  h2{font-size:2rem;color:var(--green);margin-bottom:12px}
  .lead{color:var(--muted);max-width:640px;margin-bottom:8px}
  .rule{width:56px;height:4px;background:var(--gold);margin:0 0 22px;border:0}
  .values{display:grid;grid-template-columns:repeat(auto-fit,minmax(230px,1fr));gap:28px;margin-top:30px}
  .values h3{font-size:1.15rem;color:var(--green);margin-bottom:6px}
  .values p{color:var(--muted);font-size:.96rem}
  .programs{display:grid;grid-template-columns:repeat(auto-fit,minmax(230px,1fr));gap:20px;margin-top:30px}
  .prog{background:var(--paper);border:1px solid var(--line);border-top:4px solid var(--green);padding:22px;border-radius:4px;display:flex;flex-direction:column}
  .prog h3{font-size:1.2rem;color:var(--green);margin-bottom:8px}
  .prog p{color:var(--muted);font-size:.95rem;flex:1;margin-bottom:14px}
  .prog a{font-weight:600;color:var(--green2);text-decoration:none;font-size:.95rem}
  .prog a:hover{text-decoration:underline}
  .two{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:40px;margin-top:20px}
  .box{background:var(--white);border:1px solid var(--line);border-radius:4px;padding:26px}
  .box h3{color:var(--green);margin-bottom:12px;font-size:1.2rem}
  .box ul{margin-left:20px;color:var(--ink)}
  .box li{margin-bottom:6px}
  .steps{list-style:none;counter-reset:s}
  .steps li{counter-increment:s;position:relative;padding:0 0 18px 50px;margin:0}
  .steps li::before{content:counter(s);position:absolute;left:0;top:0;width:34px;height:34px;border-radius:50%;background:var(--green);color:#fff;display:grid;place-items:center;font-weight:600}
  .steps strong{display:block}
  .steps span{color:var(--muted);font-size:.95rem}
  .contact{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:20px;margin-top:26px}
  .contact div{background:var(--paper);border:1px solid var(--line);border-radius:4px;padding:20px}
  .contact h3{font-size:1rem;color:var(--green);margin-bottom:4px}
  .contact p{color:var(--muted);overflow-wrap:anywhere}
  footer{background:var(--ink);color:#c5cdc7;padding:34px 0;font-size:.9rem}
  footer .wrap{display:flex;flex-wrap:wrap;justify-content:space-between;gap:10px 20px}
  footer a{text-decoration:none;margin-right:16px}
  footer a:hover{color:var(--gold)}
  a:focus-visible{outline:3px solid var(--gold);outline-offset:3px}
  @media (max-width:640px){html{scroll-padding-top:140px}.hero{padding:64px 0}section{padding:52px 0}nav{gap:4px 14px}}
</style>
</head>
<body>

<div class="topbar">
  <div class="wrap">
    <span>Admissions open</span>
    <span>butrusfaith@gmail.com &nbsp;|&nbsp; +256 748 359 324</span>
  </div>
</div>

<header>
  <div class="wrap">
    <a class="brand" href="#home" aria-label="Bugema University home">
      <span class="logo">BU</span>
      <span><b>Bugema University</b><small>Excellence in service</small></span>
    </a>
    <nav aria-label="Main">
      <a href="#about">About</a>
      <a href="#programs">Programs</a>
      <a href="#admissions">Admissions</a>
      <a href="#portal">Students</a>
      <a href="#contact">Contact</a>
      <a class="cta" href="#admissions">Apply now</a>
    </nav>
  </div>
</header>

<main id="home">
  <div class="hero">
    <div class="wrap">
      <h1>Learn. Grow. Lead with purpose.</h1>
      <p>Bugema University prepares students for their careers with quality education, practical skills and Christian values.</p>
      <a class="btn gold" href="#admissions">Start your application</a>
      <a class="btn line" href="#programs">Explore programs</a>
    </div>
  </div>

  <section id="about">
    <div class="wrap">
      <h2>About the university</h2>
      <hr class="rule">
      <p class="lead">We help students grow academically, professionally and spiritually, in a learning environment that prepares them for the world of work.</p>
      <div class="values">
        <div><h3>Quality education</h3><p>Courses designed to build real knowledge and skills.</p></div>
        <div><h3>Career preparation</h3><p>Learning that connects classroom ideas to future careers.</p></div>
        <div><h3>Christian values</h3><p>A community that values integrity, service and faith.</p></div>
      </div>
    </div>
  </section>

  <section id="programs" class="alt">
    <div class="wrap">
      <h2>Academic programs</h2>
      <hr class="rule">
      <p class="lead">Choose a field of study that matches your goals.</p>
      <div class="programs">
        <div class="prog"><h3>Information Technology</h3><p>Computer systems, programming, networking and modern technology.</p><a href="#admissions">How to apply</a></div>
        <div class="prog"><h3>Business Administration</h3><p>Management, entrepreneurship and leadership skills.</p><a href="#admissions">How to apply</a></div>
        <div class="prog"><h3>Education</h3><p>Professional training for a career in teaching.</p><a href="#admissions">How to apply</a></div>
        <div class="prog"><h3>Health Sciences</h3><p>Knowledge and skills for careers in health care.</p><a href="#admissions">How to apply</a></div>
      </div>
    </div>
  </section>

  <section id="admissions">
    <div class="wrap">
      <h2>Admissions</h2>
      <hr class="rule">
      <p class="lead">Applying is simple. Follow the steps and prepare your documents.</p>
      <div class="two">
        <div class="box">
          <h3>How to apply</h3>
          <ol class="steps">
            <li><strong>Choose a program</strong><span>Select the course you want to study.</span></li>
            <li><strong>Complete the application</strong><span>Fill in the university application form.</span></li>
            <li><strong>Submit your documents</strong><span>Send your certificates and ID.</span></li>
            <li><strong>Receive your result</strong><span>The university will contact you.</span></li>
          </ol>
        </div>
        <div class="box">
          <h3>Required documents</h3>
          <ul>
            <li>Academic certificates</li>
            <li>Valid identification</li>
            <li>Passport-size photographs</li>
            <li>Completed application form</li>
            <li>Any other required documents</li>
          </ul>
          <p style="margin-top:20px"><a class="btn gold" href="#contact">Contact admissions</a></p>
        </div>
      </div>
    </div>
  </section>

  <section id="portal" class="alt">
    <div class="wrap">
      <h2>Current students</h2>
      <hr class="rule">
      <p class="lead">Need help with courses, results or university services? Contact the registrar's office and they will assist you.</p>
      <p style="margin-top:18px"><a class="btn gold" href="#contact">Contact the registrar</a></p>
    </div>
  </section>

  <section id="contact">
    <div class="wrap">
      <h2>Contact us</h2>
      <hr class="rule">
      <p class="lead">Questions about admissions, programs or services? We are happy to help.</p>
      <div class="contact">
        <div><h3>Location</h3><p>Main Campus, Kalagala, Luweero District, Uganda<br>Gayaza–Ziroobwe Road, about 33 km north of Kampala</p></div>
        <div><h3>Email</h3><p>butrusfaith@gmail.com</p></div>
        <div><h3>Phone</h3><p>+256 748 359 324</p></div>
      </div>
    </div>
  </section>
</main>

<footer>
  <div class="wrap">
    <span>&copy; 2026 Bugema University. All rights reserved.</span>
    <span><a href="#about">About</a><a href="#programs">Programs</a><a href="#admissions">Admissions</a><a href="#contact">Contact</a></span>
  </div>
</footer>

</body>
</html>
