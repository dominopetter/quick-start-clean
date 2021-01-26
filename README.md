Welcome to your very own Domino quick-start project!

This project has examples for running batch jobs, iterating using workspaces, publishing models as APIs, and publishing Python/Flask and R/Shiny web applications.

_Before you get started, you might want to check out [our product tour video](https://www.dominodatalab.com/p/weekly-live-demo-ungated/)._

### Run Batch Jobs

Domino makes it easy to run a file written in your language of choice as a job, and you can start jobs on the Jobs dashboard, available by clicking on "Jobs" in the project nav.

By default, your jobs will run on the default hardware tier for your project. You can choose a different hardware tier when launching a job, and you can easily change the default hardware tier inside of your project's [Settings](settings).

In the `main.*` files, you will find code samples in Python and R to write to `stdout`, chart a histogram with random numbers, and write key run statistics to `dominostats.json`.

Try running one of these files twice and use the compare run functionality on the Jobs dashboard to see how the output, charts, and key statistics have changed!

### Iterate with Workspaces

Interactive tools like JupyterLab and RStudio are popular applications in which to do and share quantitative research. Domino lets you spin up a workspace with the click of a button on the Workspaces dashboard of a project, which you can get to through the "Workspaces" link to the left.

`main.ipynb` is a sample Jupyter notebook with code similar to `main.py`. Take note how the notebook lets you intermingle Markdown, input, and output code all in one document. When browsing files from the [Files](browse) page, Domino will render your notebook as you'd expect and you can even schedule your notebook to run and email you using [scheduled jobs](scheduledruns).

### Publish a Model as an API

Domino makes it easy to [publish your R or Python model as a web service](endpoints/modelManager) too, available by clicking on "Publish" and then "Model APIs" in the left nav.

`model.py` and `model.R` have `my_model` functions. By simply specifying the file and function name, you can have a REST API for your model set up in no time.

### Publish an App

You can also use Domino to [deploy a web app](app) to publish dashboards and enable broader data and information sharing. This functionality is available by clicking on "App" underneath "Publish" on the left.

`app.R` is an interactive R/Shiny example, `app-flask.py` is a Python/Flask example, and `app-dash.py` is a Python/Dash example of this functionality. These are used in `app.sh`, where you tell Domino which file contains your web app.

### Knowledge Management and Sharing

Right now, you're reading the `README.md` file which is a great place to explain what your project is all about.  We suggest every project have a README file -- it helps others onboard onto your project quickly and helps you remember what the point of your project was in the first place :)

README files get shown on a project's overview page and, like all files, get automatically versioned for your convenience and time traveling needs. You can even embed images from the web or your project, for example `benefits.png`:

![Benefits of Domino](raw/latest/benefits.png?inline=true "Benefits of Domino")

Want to share this project with others? Domino makes it easy for multiple people to collaborate on a project, or to share your projects publicly. [You can add collaborators to this project or adjust its visibility here.](settings#sharing)

_____

**Need some extra help?**

* Simply email [support@dominodatalab.com](mailto:support@dominodatalab.com) or click the blue circular help icon to ask for help without leaving Domino.
* We've also got a ton of great content on [docs.dominodatalab.com](https://docs.dominodatalab.com)
