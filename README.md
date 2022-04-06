# Deep Nets Art Style Transfer

This project demonstrates how to use deep neural networks to generate stylized images given an input image and an input art style.

<div style="display:flex; justify-content:center; align-items:center;">
  <img 
     src="https://github.com/FrederickRoman/DeepNetsArtStyleTransfer/blob/master/cats.jpg"  
     width="20%" 
     width="20%" 
     alt="base image (cats)"
   />
   <img 
    src="https://github.com/FrederickRoman/DeepNetsArtStyleTransfer/blob/master/Vassily_Kandinsky,_1913_Composition_7.jpg" 
    width="40%" 
    alt="style reference image (Vassily Kandinsky painting)"
  />
   <img 
      src="https://github.com/FrederickRoman/DeepNetsArtStyleTransfer/blob/master/style_transfer_demo.gif"  
      width="20%" 
      alt="style transfer demo gif" 
    />
</div>

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

