# SeeFood
## Abstract
SeeFood is a project that took inspiration from the TV Show "Silicon Valley" where a "Shazam for Food" was pitched and built. We built a food classifier with 101 classes trained on the "Food-101" dataset from ETH Zürich. After some experimentation with different modlels and a subset of our data, we decided to use transfer learning on a ResNet-50 model trained on everyday images and implemented our own head to accomplish our food classification objective.

Read more about our project here: 
## Experimentation Results
### ResNet-50 results
```python
#ResNet50 accuracy graph
plt.title("ResNet50")
plt.plot(history.history['accuracy'])
plt.plot(history.history['val_accuracy'])
plt.ylabel('accuracy')
plt.xlabel('epoch')
plt.legend(['train_accuracy', 'validation_accuracy'], loc='best')
plt.show()
#ResNet50 loss graph
plt.title("ResNet50")
plt.plot(history.history['loss'])
plt.plot(history.history['val_loss'])
plt.ylabel('loss')
plt.xlabel('epoch')
plt.legend(['train_loss', 'validation_loss'], loc='best')
plt.show()
```

### MobileNetV2 results
```python
#MobileNetV2 accuracy graph
plt.title("MobileNetV2")
plt.plot(history.history['accuracy'])
plt.plot(history.history['val_accuracy'])
plt.ylabel('accuracy')
plt.xlabel('epoch')
plt.legend(['train_accuracy', 'validation_accuracy'], loc='best')
plt.show()
#MobileNetV2 loss graph
plt.title("MobileNetV2")
plt.plot(history.history['loss'])
plt.plot(history.history['val_loss'])
plt.ylabel('loss')
plt.xlabel('epoch')
plt.legend(['train_loss', 'validation_loss'], loc='best')
plt.show()
```

### EfficientNetB0 results
```python
#EfficientNetB0 accuracy graph
plt.title("EfficientNetB0")
plt.plot(history.history['accuracy'])
plt.plot(history.history['val_accuracy'])
plt.ylabel('accuracy')
plt.xlabel('epoch')
plt.legend(['train_accuracy', 'validation_accuracy'], loc='best')
plt.show()
#EfficientNetB0 loss graph
plt.title("EfficientNetB0")
plt.plot(history.history['loss'])
plt.plot(history.history['val_loss'])
plt.ylabel('loss')
plt.xlabel('epoch')
plt.legend(['train_loss', 'validation_loss'], loc='best')
plt.show()
```



