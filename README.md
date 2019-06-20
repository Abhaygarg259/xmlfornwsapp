# xmlfornwsapp
//lets see

<?xml version="1.0" encoding="utf-8"?>

<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@drawable/wp1934020"
    app:layout_behavior="@string/appbar_scrolling_view_behavior"
    tools:context=".MainActivity"
    tools:showIn="@layout/activity_main">


    <Spinner
        android:id="@+id/spinner"
        android:layout_width="277dp"
        android:layout_height="71dp"
        android:layout_marginBottom="338dp"
        android:spinnerMode="dropdown"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_chainStyle="spread_inside"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintVertical_chainStyle="spread_inside" />

    <TextView
        android:id="@+id/textView4"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:gravity="center"
        android:padding="20dp"
        android:text="NEWS"
        android:textColor="@color/colorPrimaryDark"
        android:textSize="36sp"
        android:typeface="serif"
        android:textStyle="bold"
        tools:layout_editor_absoluteX="0dp"
        tools:layout_editor_absoluteY="16dp" />


</androidx.constraintlayout.widget.ConstraintLayout>
