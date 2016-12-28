SparkGen
========

# Motivation

 Organizations are moving towards a configuration driven data warehousing (Extract, Transform, load) methodology. This methodology abstracts the intricacies of a technology stack in a big data environment and exposes only the necessary details that are needed for a software engineer/Dev-Ops to run a Big data job. Such a boilerplate helps us to reuse the code efficiently for different types of job by just changing the variables that we want to pass for that job to run. So now we write these important parameters in a configuration file and write job execution scripts which takes its parameters from the configuration files. I was working with a configuration file format called YAML (Yet Another Markup Language). But writing jobs in the configuration files did not scale well in the organization where I worked. I can attribute two reasons.

    * Data warehousing jobs were becoming complex
    * Developers were making lot of indentation and spelling mistakes while configuring a job.

Our team came up with an idea to automate job configuration process with a methodology. you can find it [here](./SparkGen Version 2.pdf).

  Since this is a proprietary tool, I cannot share the code. But readers can of course get an idea on the methodology.

