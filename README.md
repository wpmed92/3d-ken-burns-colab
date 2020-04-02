# 3d-ken-burns Google Colab notebook

This project aims to help those who want to quickly try out and play with [3d-ken-burns](https://github.com/sniklaus/3d-ken-burns)

## How to use
Just open the notebook in Google Colab, enable GPU in your runtime, and go through the steps.
Once the original git repo is cloned, modify the requirements.txt file and delete a the cupy line, because Colab can't install that.
It will be installed in another separate step.
The step that actually performs the autoparalax is this:

```
python autozoom.py --in ./images/doublestrike.jpg --out ./magic.mp4
```

You can drag and drop your own images in Colab, and update the `--in ./path/to/your/image.jpg` part accordingly.

## References

```
[1]  @article{Niklaus_TOG_2019,
         author = {Simon Niklaus and Long Mai and Jimei Yang and Feng Liu},
         title = {3D Ken Burns Effect from a Single Image},
         journal = {ACM Transactions on Graphics},
         volume = {38},
         number = {6},
         pages = {184:1--184:15},
         year = {2019}
     }
```
