---
type: docs
no_list: true
title: "Step 1. Setting up the environment"
linkTitle: "Step 1. Environment setup"

---

Before we can start writing-up some microservices, we’ll need to install a few mandatory prerequisites.

### 1. Compiler and IDE

First and foremost - we’ll need a compiler for your programming language of choice, as well as some sort of code editor. In our examples, we usually use Visual Studio Code, but any fitting IDE will do.

For working with the Python programming language, you’ll need to perform its installation and setup the environment. To do this, download and install Python from their [official site](https://www.python.org/downloads/) . Select the download that corresponds to the operating system you’re using, and follow the installation instructions listed on their site.

Once installed, check that the installation was completed successfully by running the following command from your console:

<div class="content-tab-selector">
	<div class="btn-group tab-selector-btn-group" role="group" aria-label="Language selector">
	  <button type="button" class="btn lang-select-btn">Node</button>
	  <button type="button" class="btn lang-select-btn">.NET</button>
	  <button type="button" class="btn lang-select-btn">Golang</button>
	  <button type="button" class="btn lang-select-btn">Dart</button>
	  <button type="button" class="btn lang-select-btn">Python</button>
	  <button type="button" class="btn lang-select-btn">Java</button>
	</div>

<div class="content-tab-section">
  {{< include "/content/en/toolkit/tutorials/data_microservice/__code1_node.md" >}}  
</div>

<div class="content-tab-section">
  {{< include "/content/en/toolkit/tutorials/data_microservice/__code1_net.md" >}}    
</div>

<div class="content-tab-section">
  Not available  
</div>

<div class="content-tab-section">
  {{< include "/content/en/toolkit/tutorials/data_microservice/__code1_dart.md" >}}    
</div>

<div class="content-tab-section">
  {{< include "/content/en/toolkit/tutorials/data_microservice/__code1_python.md" >}}
</div>

<div class="content-tab-section">
  Not available  
</div>

</div>


### 2. MongoDB
Data microservice examples use MongoDB for storing data. You can either install MongoDB locally on your computer, or start it in a docker container.

To install MongoDB locally, download the installer from their [official website](https://www.mongodb.org/downloads) . Select the download that corresponds to the operating system you’re using, and follow the installation instructions listed on their site.

### 3.Docker
To install Docker, download the Docker Desktop installer that corresponds to the operating system you’re using from the official [Docker site](https://www.docker.com/get-started). Once downloaded, launch the installer and follow the installation instructions.

Once installed, check that the installation was completed successfully by running the following commands from your console:

```bash
docker --version
```

If everything was installed successfully, the screen will display the latest version of Docker.

Now that we’ve got the environment set up, we can move on to [Step 2. Setting up the project.](../step1)

<span class="hide-title-link">

### [Step 2. Setting up the project.](../step1)

</span>
