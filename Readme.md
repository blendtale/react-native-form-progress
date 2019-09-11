# React Native Form progress 

A react native component super useful in displaying progress when user is filling up forms like signup page, setting, information catering etc


## Installing 

```npm i react-native-form-prorgress```

### Using 

```import ProgressBar from react-native-form-prorgress```

And then 

```
	<ProgressBar 
					currentProgress={7} 
					totalNumberOfProgressBars={8}
					colorOfProgressBar="#2E7D32"
					 />
```

and just keep incrementing current progress 

### Working GIFS 

### With blink 

![ezgif com-video-to-gif](https://user-images.githubusercontent.com/32276134/64683540-1180fd00-d4a1-11e9-9711-c87b2905b8d4.gif)

### Without Blink 



###  Props 

| **Prop** | **Type** | **Default** | **Required** | **description** |
|----------|----------|-------------|--------------|--------------|
| colorOfProgressBar | string | 'black' | No | What Color do you want your progress bar to have 
| colorOfNonProgressBar | string | 'white' | No | the space progress bar is yet to take |
| currentProgress | number | none | Yes | the current progress of your progress bar, **increment this value** on sucessful completion of event |
| totalNumberOfProgressBars | number | none | Yes | Typical this determines how many boxes should progress bar have in all together | 
| heightOfProgressBar | number | 5 | No | what should be the height of your progress bar |
| SafeAreaViewDeciderProps | object | ```	SafeAreaViewDeciderProps: {statusBarHiddenForNotch: false, statusBarHiddenForNonNotch: false}``` | No | Takes [SafeAreaViewDeciderProps](https://www.npmjs.com/package/react-native-smart-statusbar) Props as an object |
| 	blink | boolean | true | No | Do you wan the progress bar to blink or not | 
|   durationForTheBlink | false | 500 | how fast you want the blink to happen



