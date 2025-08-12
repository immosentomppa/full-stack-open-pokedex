<h2>Some common steps in a CI setup include linting, testing, and building. What are the specific tools for taking care of these steps in the ecosystem of the language you picked?</h2>
<b>Chosen language: Python</b>
<h3>Linting</h3>
<p>For Python, some of the linting examples include:</p>
<ul>
  <li>Pylint: seems to be one of the more popular linting options for Python. It contains the basic functionalities like PEP 8 (Python's style guide) checking, error detection and editor integrations. In addition, it even has support for UML diagrams. It also has an extensive documentation</li>
  <li>Flake8: this one is actually a wrapper around PyFlakes, pycodestyle & Ned Batchelder’s McCabe script. The first one includes functionalities to perform PEP 8 checks, the second one checks the Python source files for errors, and the last one is a complexity checker tool</li>
  <li>Mypy is more of a static type checker than an overall linter. Mypy helps the programmer to ensure they're using variables/functions correctly in their code, and it provides PEP 484 type hinting capabilities.</li>
</ul>
<h3>Testing</h3>
<p>The testing tools for Python include the folloxing tools:
<ul>
  <li>Pytest: one of the more popular testing tools. The pytest framework aims to provide easy tools for writing tests that are small and readable, while also offering scaling support when complex functional testing is needed</li>
  <li>Robot Framework: this one is available not only for Python, but for other languages also. It provides framework for test automation and robot process automation, and is said to be widely used in the industry. It provides syntax that is human-friendly and versatile using keywords, and it supports extension through various libraries</li>
  <li>Selenium WebDriver: The Selenium WebDriver is targeted to complete tests in the graphical environment offered by browsers, through programming-like syntax that is used to communicate with APIs. In addition to the WebDriver, Selenium also offers their own IDE as a browser extension, and Grid to run test cases on different machines.</li>
</ul>
<h3>Building</h3>
<p>Python doesn't explicitly need building thanks to the default CPython reference implementation which compiles and interprets Python code when it's executed. Still, some Python building tools exists, making distributing the code in packages easier, as it needs for example name, version and dependencies. Examples of building tools are listed below:</p>
<ul>
  <li>setuptools: this tool has been around for two decades, and it has grown to rather complex tool. Enables for example building and distributing Python packages, especially ones with dependencies to other packages</li>
  <li>Hatcling: a more modern alternative to setuptools. This is a build backend for Hatch, which is a more full-featured project management tool</li>
  <li>flit: very minimal, enables packaging pure Python projects and is great for small/medium projects with no build-time custom logic.</li>
</ul>

<h2>What alternatives are there to set up the CI besides Jenkins and GitHub Actions?</h2>
CI alternatives to Jenkins & GitHub Actions include the following:
<ul>
  <li>GitLab CI/CD: GitLab is somewhat similar to GitHub, was built to improve GitHub's overall experience. Offers their own cloud-based CI/CD solutions</li>
  <li>AWS CodePipeline: AWS's CI/CD tool, can directly interface with other existing AWS tool for enhanced experience</li>
  <li>Azure Pipelines: Azure's CI/CD tool, can similarly be integrated to Azure services like AWS CodePipeline.</li>
</ul>
<h2>Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?</h2>
<p>I think that because the goal here is to learn CI/CD functionalities rather than the setup of an infrastructure which would come in a self-hosted environment, cloud-based is better here. Maybe if there would be a self-hosted one without additional hassle that could be compared to e.g. GitHub Actions because of its user-friendly setup on some virtual machine etc., they both would be relevant.</p>
