# m_flask_template
<p>This is a modularized flask template, ready to go.</p>
<p>Template credit and thanks to: rteet702</p>
<p>This template is used with bashrc code to clone the template into a new project directory. 
  To get the full benefit of this template, add the following code snippets to your bashrc file:</p>
  
  ```bash
  function pys(){
      pipenv shell && echo "-------------------VIRTUAL ENVIRONMENT LAUNCHED-------------------"
      python server.py && echo "-------------------- RUN SERVER --------------------"
  }
  export -f pys
  
  function gitmflasktemplate(name){
      mkdir $name && echo "------------------- CREATING NEW PROJECT DIRECTORY -------------------"
      cd $name && echo "------------------- CHANGING INTO PROJECT DIRECTORY -------------------"
      git clone https://github.com/code-Brian/m_flask_template.git && echo "------------------- GIT REPO CLONED -------------------"
      rm -r .git && echo "------------------- GIT FILE DELETED -------------------"
      pyi() && echo "------------------- INSTALLING FLASK AND PYMYSQL -------------------"
  }
  export -f gitmflasktemplate
  ```
<p> I hope this template is helpful. Please ping myself or Robert (rteet702) if there are any questions!</p>
