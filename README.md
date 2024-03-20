<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <LinearLayout
        android:id="@+id/linearLayout"
        android:layout_width="409dp"
        android:layout_height="80dp"
        android:orientation="vertical"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.024">

        <EditText
            android:id="@+id/display"
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:ems="10"
            android:inputType="text"
            android:hint="saisie des chiffres " />
    </LinearLayout>

    <LinearLayout
        android:id="@+id/linearLayout2"
        android:layout_width="409dp"
        android:layout_height="60dp"
        android:orientation="vertical"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.202">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="60dp"
            android:orientation="horizontal"
            android:layout_marginStart="10dp"
            android:layout_marginEnd="20dp">

            <Button
                android:id="@+id/btn_clear"
                android:backgroundTint="#4C4949"
                android:textSize="28dp"
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="AC" />

            <Button
                android:backgroundTint="#4C4949"

                android:id="@+id/button18"
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="+/-"
                android:textSize="28dp"
                android:layout_marginStart="3dp"
                android:layout_marginEnd="2dp"/>

            <Button
                android:backgroundTint="#4C4949"

                android:id="@+id/button25"
                android:textSize="28dp"
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="%"
                android:layout_marginStart="2dp"
                android:layout_marginEnd="2dp"/>

            <Button
                android:backgroundTint="#4C4949"

                android:id="@+id/button99"
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:textSize="28dp"
                android:text="/" />
        </LinearLayout>
    </LinearLayout>
    <LinearLayout
        android:id="@+id/linearLayout3"
        android:layout_width="409dp"
        android:layout_height="60dp"
        android:orientation="vertical"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.202"
        android:layout_marginTop="100dp">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="60dp"
            android:orientation="horizontal"
            android:layout_marginStart="10dp"
            android:layout_marginEnd="20dp">

            <Button
                android:backgroundTint="#4C4949"
                android:id="@+id/btn_0"
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="1"
                android:textSize="28dp"/>

            <Button
                android:id="@+id/btn_1"
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="2"
                android:textSize="28dp"
                android:backgroundTint="#4C4949"
                android:layout_marginStart="3dp"
                android:layout_marginEnd="2dp"/>

            <Button
                android:backgroundTint="#4C4949"
                android:id="@+id/btn_2"
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="3"
                android:textSize="28dp"
                android:layout_marginStart="2dp"
                android:layout_marginEnd="2dp"/>

            <Button
                android:id="@+id/btn_multiply"
                android:backgroundTint="#4C4949"
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:textSize="28dp"
                android:text="*" />
        </LinearLayout>
    </LinearLayout>
    <LinearLayout
        android:id="@+id/linearLayout4"
        android:layout_width="409dp"
        android:layout_height="60dp"
        android:orientation="vertical"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.202"
        android:layout_marginTop="190dp">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="60dp"
            android:orientation="horizontal"
            android:layout_marginStart="10dp"
            android:layout_marginEnd="20dp">

            <Button
                android:id="@+id/button35"
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="7" />

            <Button
                android:id="@+id/button36"
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="Button"
                android:layout_marginStart="3dp"
                android:layout_marginEnd="2dp"/>

            <Button
                android:id="@+id/button19"
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="Button"
                android:layout_marginStart="2dp"
                android:layout_marginEnd="2dp"/>

            <Button
                android:id="@+id/button20"
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="Button" />
        </LinearLayout>
    </LinearLayout>
    <LinearLayout
        android:id="@+id/linearLayout5"
        android:layout_width="409dp"
        android:layout_height="60dp"
        android:orientation="vertical"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.202"
        android:layout_marginTop="190dp">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="60dp"
            android:orientation="horizontal"
            android:layout_marginStart="10dp"
            android:layout_marginEnd="20dp">

            <Button
                android:backgroundTint="#4C4949"
                android:id="@+id/btn_3"
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="4"
                android:textSize="28dp"/>

            <Button
                android:backgroundTint="#4C4949"
                android:id="@+id/btn_4"
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="5"
                android:textSize="28dp"
                android:layout_marginStart="3dp"
                android:layout_marginEnd="2dp"/>

            <Button
                android:id="@+id/btn_5"
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="6"
                android:backgroundTint="#4C4949"

                android:textSize="28dp"
                android:layout_marginStart="2dp"
                android:layout_marginEnd="2dp"/>

            <Button
                android:id="@+id/btn_subtract"
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:textSize="28dp"
                android:backgroundTint="#4C4949"

                android:text="-" />
        </LinearLayout>
    </LinearLayout>
    <LinearLayout
        android:id="@+id/linearLayout6"
        android:layout_width="409dp"
        android:layout_height="60dp"
        android:orientation="vertical"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.202"
        android:layout_marginTop="290dp">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="60dp"
            android:orientation="horizontal"
            android:layout_marginStart="10dp"
            android:layout_marginEnd="20dp">

            <Button
                android:id="@+id/btn_6"
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:textSize="28dp"
                android:backgroundTint="#4C4949"

                android:text="7" />

            <Button
                android:id="@+id/btn_7"
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="8"
                android:backgroundTint="#4C4949"
                android:textSize="28dp"
                android:layout_marginStart="3dp"
                android:layout_marginEnd="2dp"/>

            <Button
                android:id="@+id/btn_8"
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="9"
                android:backgroundTint="#4C4949"

                android:textSize="28dp"
                android:layout_marginStart="2dp"
                android:layout_marginEnd="2dp"/>

            <Button
                android:id="@+id/btn_add"
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:textSize="28dp"
                android:backgroundTint="#4C4949"

                android:text="+" />
        </LinearLayout>
    </LinearLayout>

    <LinearLayout

        android:id="@+id/linearLayout7"
        android:layout_width="match_parent"
        android:layout_height="60dp"
        android:orientation="vertical"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.655">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:layout_marginStart="10dp"
            android:layout_marginEnd="20dp"
            android:orientation="horizontal">

            <Button
                android:id="@+id/btn_9"
                android:layout_width="20dp"
                android:layout_height="match_parent"
                android:layout_marginStart="99dp"
                android:layout_marginEnd="25dp"
                android:layout_weight="1"
                android:backgroundTint="#4C4949"
                android:text="0"
                android:textSize="28dp" />

            <Button
                android:id="@+id/btn_equal"
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:layout_marginStart="5dp"
                android:layout_weight="1"
                android:text="="
                android:backgroundTint="#4C4949"
                android:textSize="28sp"/>
        </LinearLayout>
    </LinearLayout>

    <EditText
        android:id="@+id/editTextText3"
        android:layout_width="250dp"
        android:layout_height="50dp"
        android:ems="10"
        android:inputType="text"
        android:text=""
        android:hint="Résultat"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/linearLayout7" />


</androidx.constraintlayout.widget.ConstraintLayout>
