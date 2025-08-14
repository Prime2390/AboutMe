<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>About Me - Dominik Bernaś</title>
<style>
  body {
    font-family: Arial, sans-serif;
    max-width: 900px;
    margin: 0 auto;
    padding: 20px;
    line-height: 1.6;
  }
  .lang-switch {
    text-align: right;
    margin-bottom: 15px;
  }
  button {
    background: #007BFF;
    color: #fff;
    border: none;
    padding: 6px 12px;
    margin-left: 5px;
    border-radius: 4px;
    cursor: pointer;
    font-size: 14px;
  }
  button:hover {
    background: #0056b3;
  }
  .lang-content {
    display: none;
  }
  .lang-content.active {
    display: block;
  }
  h2 {
    margin-top: 25px;
    color: #333;
  }
  a {
    color: #007BFF;
    text-decoration: none;
  }
  a:hover {
    text-decoration: underline;
  }
</style>
</head>
<body>

<div class="lang-switch">
  <button onclick="switchLang('en')">🇬🇧 English</button>
  <button onclick="switchLang('pl')">🇵🇱 Polski</button>
</div>


<div id="lang-en" class="lang-content active">
  <h2>👋 About Me</h2>
  <p>
    Hi! My name is <strong>Dominik Bernaś</strong> and I’m a passionate 
    <strong>Junior Software Tester</strong> with a strong interest in both 
    <strong>manual</strong> and <strong>automated testing</strong>.  
    I’m currently working at <strong>Quality Island</strong>, where I have hands-on experience in:
  </p>
  <ul>
    <li>Testing administrative and configuration features in the platform</li>
    <li>Designing and executing detailed test scenarios</li>
    <li>Working with both front-end and back-end functionalities</li>
  </ul>
  <p>
    My journey in QA started with <strong>manual testing</strong> and bug reporting, but over time 
    I expanded my skillset into <strong>test automation</strong> using Selenium WebDriver with Java, 
    the Page Object Model (POM) framework, and REST API testing with Postman and REST Assured.  
    I’m also familiar with <strong>SQL</strong> for database verification and I enjoy 
    <strong>exploratory testing</strong> to uncover unexpected issues.
  </p>
  <p>
    I believe that high-quality software comes from attention to detail, 
    clear communication, and continuous learning — so I’m always looking for new challenges and ways to improve my testing approach.
  </p>

  <h2>🛠 Skills</h2>
  <ul>
    <li>✅ Manual Testing & Bug Reporting</li>
    <li>✅ Test Automation (Selenium WebDriver – Java, POM)</li>
    <li>✅ SQL for Database Testing</li>
    <li>✅ API Testing (Postman, REST Assured)</li>
    <li>✅ Test Case Design & Execution</li>
    <li>✅ Exploratory & Performance Testing</li>
  </ul>

  <h2>📂 Projects</h2>
  <ul>
    <li>
      <strong>Publigo</strong> – 
      <a href="https://github.com/Prime2390/Publigo" target="_blank">
        View on GitHub
      </a>
    </li>
    <li>
      <strong>ParaBank Testing Suite</strong> – 
      <a href="https://github.com/Prime2390/ParaBank-TestingSuite" target="_blank">
        View on GitHub
      </a>
    </li>
  </ul>
</div>


<div id="lang-pl" class="lang-content">
  <h2>👋 O mnie</h2>
  <p>
    Cześć! Nazywam się <strong>Dominik Bernaś</strong> i jestem 
    <strong>Junior Software Testerem</strong> z dużym zainteresowaniem 
    <strong>testowaniem manualnym</strong> oraz <strong>automatycznym</strong>.  
    Obecnie pracuję w firmie <strong>Quality Island</strong>, gdzie mam praktyczne doświadczenie w:
  </p>
  <ul>
    <li>Testowaniu funkcji administracyjnych i konfiguracyjnych platformy</li>
    <li>Projektowaniu i wykonywaniu szczegółowych scenariuszy testowych</li>
    <li>Pracy z funkcjonalnościami zarówno po stronie front-end, jak i back-end</li>
  </ul>
  <p>
    Moja przygoda z QA zaczęła się od <strong>testów manualnych</strong> i raportowania błędów, 
    jednak z czasem poszerzyłem umiejętności o <strong>automatyzację testów</strong> 
    z wykorzystaniem Selenium WebDriver w języku Java, frameworka Page Object Model (POM) 
    oraz testowania API przy pomocy Postmana i REST Assured.  
    Znam również <strong>SQL</strong> do weryfikacji baz danych i chętnie wykonuję 
    <strong>testy eksploracyjne</strong>, aby znaleźć nieoczywiste problemy.
  </p>
  <p>
    Wierzę, że wysokiej jakości oprogramowanie powstaje dzięki dbałości o szczegóły, 
    dobrej komunikacji i ciągłemu rozwojowi — dlatego zawsze szukam nowych wyzwań 
    i sposobów na udoskonalenie mojego podejścia do testów.
  </p>

  <h2>🛠 Umiejętności</h2>
  <ul>
    <li>✅ Testy manualne i raportowanie błędów</li>
    <li>✅ Automatyzacja testów (Selenium WebDriver – Java, POM)</li>
    <li>✅ SQL do testowania baz danych</li>
    <li>✅ Testy API (Postman, REST Assured)</li>
    <li>✅ Projektowanie i wykonywanie przypadków testowych</li>
    <li>✅ Testy eksploracyjne i wydajnościowe</li>
  </ul>

  <h2>📂 Projekty</h2>
  <ul>
    <li>
      <strong>Publigo</strong> – 
      <a href="https://github.com/Prime2390/Publigo" target="_blank">
        Zobacz na GitHub
      </a>
    </li>
    <li>
      <strong>ParaBank Testing Suite</strong> – 
      <a href="https://github.com/Prime2390/ParaBank-TestingSuite" target="_blank">
        Zobacz na GitHub
      </a>
    </li>
  </ul>
</div>

<script>
function switchLang(lang) {
  document.querySelectorAll('.lang-content').forEach(el => {
    el.classList.remove('active');
  });
  document.getElementById('lang-' + lang).classList.add('active');
}
</script>

</body>
</html>
