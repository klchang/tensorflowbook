# _TensorFlow for Machine Intelligence_

![TensorFlow for Machine Intelligence book cover](img/book_cover.jpg)

Welcome to the official book repository for [_TensorFlow for Machine Intelligence_](https://bleedingedgepress.com/tensor-flow-for-machine-intelligence/)! Here, you'll find code from the book for easy testing on your own machine, as well as errata, and any additional content we can squeeze in down the line.

* **Code:** You'll find code for each chapter inside of the [chapters directory](https://github.com/backstopmedia/tensorflowbook/tree/master/chapters)
* **Errata:** Errata will be added to the [errata](https://github.com/backstopmedia/tensorflowbook/tree/master/errata) directory as they are discovered. Send in a pull request if you have errata to report!


## Update

* Add the directories **chapters_updated** and **tools**. 
* Files **tools/tf_update.py** and **tools/README.md** are stolen from [r1.8](https://github.com/tensorflow/tensorflow/tree/r1.8/tensorflow/tools/compatibility) branch in tensorflow repo. Its documentation is [Transition to TensorFlow 1.0](https://www.tensorflow.org/install/migration)
* Use **tools/tf_upgrade.py** to migrate the codes in **chapters** directory to tensorflow 1.x. The command used is as follows:

    ```python tools/tf_update.py --intree chapters --outtree chapters_updated```

 and **report.txt** is the output report of this migration.

