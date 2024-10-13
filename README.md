README
=====

Overview
-----
This program allows for code replication. By following the steps outlined below, you will be able to set up and replicate the program functionality as intended.

Instructions for replication
-----
This program is based on the constructure by Engel et al. (2023):
@article{ego,
  title={Integrating Machine Behavior into Human Subject Experiments: A User-friendly Toolkit and Illustrations},
  author={Engel, Christoph and Grossmann, Max R. P. and Ockenfels, Axel},
  year={2023},
}

Clone the repository from the following link: [https://github.com/mrpg/ego].

Our program is based on their construction for connecting otree and GPT. Before running our program, the prerequisites of their fundamental deployment are necessary. Follow the README.md first in their repository.

In the cloned directory, locate the following file: otree/egochat

Replacing the content or placement of code/init.py, code/welcome.html and code/chat.html.


Instructions for auto-running
-----

Our "autorun" program can only run on Microsoft Edge.

The only step is locate the code/auto_experiment_formal03.py. Using

python auto_experiment_formal03.py run
