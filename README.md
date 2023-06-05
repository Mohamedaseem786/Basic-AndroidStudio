# EXPERIMENT 1 Ex.No: 1 Write a program to create a HelloWorld Activity using all lifecycles methods to display messages.

# AIM
   TO  Write a program to create a HelloWorld Activity using all lifecycles methods to display messages.

# REQUIRED
  ANDROID STUDIO

# Basic-AndroidStudio
### Program:
~~~
Developed By:mohamed aseem p
Register Number: 212221230063
~~~
### MainActivity.java:
~~~
package com.example.project;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.widget.Toast;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Toast toast=Toast.makeText(getApplicationContext(),"OnCreate Executed",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onStart(){
        super.onStart();
        Toast toast=Toast.makeText(getApplicationContext(),"OnStart Executed",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onResume(){
        super.onResume();
        Toast toast=Toast.makeText(getApplicationContext(),"OnResume Executed",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onPause(){
        super.onPause();
        Toast toast=Toast.makeText(getApplicationContext(),"OnPause Executed",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onStop(){
        super.onStop();
        Toast toast=Toast.makeText(getApplicationContext(),"OnStop Executed",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onRestart(){
        super.onRestart();
        Toast toast=Toast.makeText(getApplicationContext(),"OnRestart Executed",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onDestroy(){
        super.onDestroy();
        Toast toast=Toast.makeText(getApplicationContext(),"OnDestroy Executed",Toast.LENGTH_LONG);
        toast.show();
    }
}
~~~
### activity_main.xml:
~~~
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World!"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout><?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World!"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout>
~~~
### Output:

![1](https://user-images.githubusercontent.com/93427224/190245524-3af46ac8-6f5e-4ab8-99aa-affecb5d21a5.png)

![2](https://user-images.githubusercontent.com/93427224/190246003-7bfac1a8-e9a0-4ae0-bc0c-2a45c211c882.png)


![3](https://user-images.githubusercontent.com/93427224/190246474-36e4683a-62eb-459e-98a9-eb8f584d107c.png)

![4](https://user-images.githubusercontent.com/93427224/190246495-336bab7d-bfb3-4c26-b617-05ff1cee84a9.png)

![5](https://user-images.githubusercontent.com/93427224/190246549-cb813ddf-68e4-4a00-81e2-0fa044ca627c.png)

![6](https://user-images.githubusercontent.com/93427224/190246584-d7d3242d-63af-48e3-a00a-77994a38fa59.png)

![7](https://user-images.githubusercontent.com/93427224/190246628-35fcdaa0-90fe-4ecc-ac6e-45a7a658c0d4.png)

### Result:
Therefore a program is return to develop a program to detect the various life cycles of an activity. The program is successfully executed.
