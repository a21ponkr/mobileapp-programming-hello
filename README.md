# Rapport

**Skriv din rapport här!**

Det jag har gjort är att jag har lagt till en bild i appen och ändrat 
texten från "Hello World!" till "Hej mitt namn är Pontus" genom att redigera content_main.xml-filen som fanns under res > layout.

För att lägga till bilden använde jag ImageView och la bilden i drawable. 

```
    <ImageView
        android:id="@+id/imageView"
        android:layout_width="341dp"
        android:layout_height="183dp"
        android:layout_marginEnd="24dp"
        android:layout_marginRight="24dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:srcCompat="@drawable/ponkron"
        tools:layout_editor_absoluteY="434dp"
        tools:ignore="ContentDescription,MissingConstraints" />

```


