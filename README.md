# Deep Nets Art Style Transfer

This project demonstrates how to use deep neural networks to generate stylized images given an input image and an input art style.

## Getting Started

git clone [repo]
style_transfer.py [path to input image] [path to input style]

### Prerequisites

python>=3.6

```
six
tensorflow
numpy
keras
scipy
```


## Running the example

```
style_transfer.py ./cats.jpg ./Vassily_Kandinsky,_1913_Composition_7.jpg
```
<img src="https://github.com/FrederickRoman/DeepNetsArtStyleTransfer/blob/master/cats.jpg" width="48%">
<img src="https://github.com/FrederickRoman/DeepNetsArtStyleTransfer/blob/master/Vassily_Kandinsky,_1913_Composition_7.jpg" width="48%">
<img src="https://github.com/FrederickRoman/DeepNetsArtStyleTransfer/blob/master/results_at_iteration_9.png">

## Deployment

Project also can be found in the Algorithmia deployment website under the title DeepNetsArtStyleTransfer
Algorithmia is an awesome tool to deploy algorithms easily, so please feel free to check it out!

## Built With

* Keras
* Tensorflow
* Scipy

## Authors

* Keras team
* Frederick Roman

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* The Keras team

