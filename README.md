# AnimatedProgressBar
I was trying to get used to this animated progress bar in hopes I can use it in a project in the future 

NB: Mostly used for splash screens

It is based on the work of Lopez Mikhael
### Demonstration
<img src="ApbAndroid.mp4"/>

### Usage
# Gradle
```
implementation 'com.mikhaellopez:circularfillableloaders:1.3.2'
```

# XML
```
<com.mikhaellopez.circularfillableloaders.CircularFillableLoaders
    android:id="@+id/circularFillableLoaders"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:src="@drawable/your_logo"
    app:cfl_border="true"
    app:cfl_border_width="12dp"
    app:cfl_progress="80"
    app:cfl_wave_amplitude="0.06"
    app:cfl_wave_color="#3f51b5" />
```
# KOTLIN
```
// Set Progress
circularFillableLoaders.setProgress(60);
// Set Wave and Border Color
circularFillableLoaders.setColor(Color.RED);
// Set Wave Amplitude (between 0.00f and 0.10f)
circularFillableLoaders.setAmplitudeRatio(0.08);
```

# JAVA
```
CircularFillableLoaders circularFillableLoaders = (CircularFillableLoaders)findViewById(R.id.yourCircularFillableLoaders);
// Set Progress
circularFillableLoaders.setProgress(60);
// Set Wave and Border Color
circularFillableLoaders.setColor(Color.RED);
// Set Wave Amplitude (between 0.00f and 0.10f)
circularFillableLoaders.setAmplitudeRatio(0.08);
```

# LICENCE
CircularImageView by Lopez Mikhael is licensed under a Apache License 2.0. Based on a work at https://github.com/gelitenight/WaveView.
