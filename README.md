# Hello-World
This is the code I used to design a business card with Android Studio
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#BDBDBD"
    android:orientation="vertical"
    android:paddingBottom="20dp"
    android:paddingLeft="20dp"
    android:paddingRight="20dp"
    android:paddingTop="20dp"
    tools:context="com.example.android.business.MainActivity">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:background="#616161"
        android:orientation="horizontal"
        android:paddingLeft="20dp"
        android:paddingTop="20dp">

        <Button
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:drawableLeft="@drawable/yin"
            android:text="DSN CONSULTS"/>
    </LinearLayout>

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:background="#616161"
        android:paddingLeft="80dp"
        android:text="Motto: He who asks shall never be lost."
        android:textColor="#000000"
        android:textSize="10sp" />

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:background="#616161"
        android:fontFamily="cursive"
        android:padding="20dp"
        android:text="*We are Career Counsellors who will help you make the right career decisions.*"
        android:textColor="#7986CB"
        android:textSize="20sp"
        android:textStyle="bold"/>

    <ImageView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:background="#616161"
        android:src="@drawable/confused"/>

    <Button
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:background="#616161"
        android:drawableLeft="@drawable/call"
        android:fontFamily="sans-serif-condensed"
        android:paddingTop="20dp"
        android:text="Confused?, Call us on 08098295612.
                Mondays - Thursdays : 9:00am - 4:00pm"
        android:textColor="#000000"
        android:textSize="10sp"
        android:textStyle="bold" />

        <Button
            android:id="@+id/tue"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:background="#616161"
            android:drawableLeft="@drawable/address"
            android:fontFamily="sans-serif-condensed"
            android:text="Adress: XYZ, YinYang road, Gbagada, Lagos state."
            android:textColor="#000000"
            android:textSize="10sp"
            android:textStyle="bold" />


</LinearLayout>
