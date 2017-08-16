# PokerTrainingFramework
Framework for training Heads up no limit hold'em AI

A simple python based framework for pitting HU NLHE bots against each other.
The framework is light weight and includes a C-based hand evaluator that is extremely fast, capable of evaluation more than 3 million 5-7 card hands per second. Also includes a PCG random number generator to improve speed and randomness.

A GUI is included to play against an AI or observe two AI's battling it out.

Usage:
Build C-extension with by running command "python3 setup.py build_ext --inplace".
