# Shujie Deng's Personal Website

Welcome to my personal academic website! I am a Machine Learning Researcher and M.Eng student in the Electrical Engineering and Computer Science Department at UC Berkeley.

## About Me

I specialize in:
- **Large Language Models (LLMs)** and their reasoning capabilities
- **Edge AI** and on-device machine learning applications  
- **Model distillation** and optimization for mobile/embedded systems
- **Natural Language Processing (NLP)** and semantic understanding
- **Retrieval Augmented Generation (RAG)** systems

## Current Research

I am currently working as a Research Assistant at the FHL Vive Center for Enhanced Reality at UC Berkeley, supervised by Allen Yang, focusing on Edge AI integration and on-device LLM applications.

## Contact

- **Email**: shujie.deng@berkeley.edu
- **LinkedIn**: [linkedin.com/in/shujiedeng/](https://linkedin.com/in/shujiedeng/)
- **GitHub**: [github.com/Shujie24](https://github.com/Shujie24)

---

*This website is built using the [academicpages template](https://github.com/academicpages/academicpages.github.io) based on the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/).*

## To run locally (not on GitHub Pages, to serve on your own computer)

1. Clone the repository and made updates as detailed above
1. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
1. Run `bundle clean` to clean up the directory (no need to run `--force`)
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. Run `bundle exec jekyll liveserve` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.

# Changelog -- bugfixes and enhancements

There is one logistical issue with a ready-to-fork template theme like academic pages that makes it a little tricky to get bug fixes and updates to the core theme. If you fork this repository, customize it, then pull again, you'll probably get merge conflicts. If you want to save your various .yml configuration files and markdown files, you can delete the repository and fork it again. Or you can manually patch. 

To support this, all changes to the underlying code appear as a closed issue with the tag 'code change' -- get the list [here](https://github.com/academicpages/academicpages.github.io/issues?q=is%3Aclosed%20is%3Aissue%20label%3A%22code%20change%22%20). Each issue thread includes a comment linking to the single commit or a diff across multiple commits, so those with forked repositories can easily identify what they need to patch.
