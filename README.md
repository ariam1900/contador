<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/counterTxt"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_ceterHorizontal="true"
        android:textSize="120sp"
        android:text="200"/>

    <LinearLayout
        android:layout_below="@id/counterTxt"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_ceterHorizontal="true"
        android:orientation="horizontal"
        android:layout_marginTop="80dp">

        <Button
            android:id="@+id/btnReiniciar"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Reiniciar conteo"
            android:textSize="40sp"/>

        <Button
            android:id="@+id/btnGuardar"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Guardar conteo"
            android:textSize="60sp"/>

        <Button
            android:id="@+id/btnVer"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Ver conteos guardados"
            android:textSize="60sp"/>

    </LinearLayout>

</android.support.constraint.ConstraintLayout>
