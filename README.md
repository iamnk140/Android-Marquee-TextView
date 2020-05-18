# Android-Marquee-TextView
Make your textview float like News Headline

## Usage

## xml code

```
<TextView
        android:id="@+id/textMarquee"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:padding="15dp"
        android:ellipsize="marquee"
        android:marqueeRepeatLimit="marquee_forever"
        android:textStyle="bold"
        android:textSize="20dp"
        android:singleLine="true"
        android:textColor="#3F51B5"
        android:text="Your headline text here" />
```

## java code

```

TextView textMarquee = findViewById(R.id.textMarquee);
        textMarquee.setSelected(true);

```
