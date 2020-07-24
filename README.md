# Mess
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"  //when i am trying to change constraint to linear its getting error//
 // same when i am trying to change horizontallinear layout to verticle//
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <LinearLayout
        android:layout_width="409dp"
        android:layout_height="729dp"
        android:orientation="horizontal"
        tools:layout_editor_absoluteX="1dp"
        tools:layout_editor_absoluteY="1dp">

        <Button
            android:id="@+id/button1"
            android:layout_width="10dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:text="Menu"
            tools:ignore="DuplicateIds" />
        <Button
            android:id="@+id/button2"
            android:layout_width="10dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:text="FoodFeedBack" />
        <Button
            android:id="@+id/button3"
            android:layout_width="10dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:text="UST" />

        <androidx.constraintlayout.widget.Guideline
            android:id="@+id/guideline"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:orientation="vertical" />

    </LinearLayout>

