Testando 

Fiz uma nova atualização 

adicionando novo arquivo 

 <Button
        android:id="@+id/btnenviar"
        android:layout_width="140dp"
        android:layout_height="64dp"
        android:layout_marginStart="160dp"
        android:layout_marginTop="40dp"
        android:layout_marginEnd="160dp"
        android:layout_marginBottom="207dp"
        android:backgroundTint="#105313"
        android:drawableTint="#4CAF50"
        android:text="@string/btnenviar"
        android:textSize="24sp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/txtsenha2" />

    <TextView
        android:id="@+id/txtlogin"
        android:layout_width="259dp"
        android:layout_height="85dp"
        android:layout_marginStart="139dp"
        android:layout_marginTop="150dp"
        android:layout_marginEnd="140dp"
        android:layout_marginBottom="23dp"
        android:fontFamily="sans-serif-black"
        android:text="@string/txtlogin"
        android:textColor="#105313"
        android:textColorHighlight="#105313"
        android:textColorHint="#105313"
        android:textColorLink="#105313"
        android:textSize="34sp"
        app:layout_constraintBottom_toTopOf="@+id/txtnome"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.409"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <EditText
        android:id="@+id/txtnome"
        android:layout_width="247dp"
        android:layout_height="51dp"
        android:layout_marginStart="101dp"
        android:layout_marginTop="25dp"
        android:layout_marginEnd="100dp"
        android:layout_marginBottom="22dp"
        android:autofillHints=""
        android:ems="10"
        android:hint="@string/txtnome"
        android:inputType="text"
        android:textColor="#105313"
        android:textColorHighlight="#105313"
        android:textColorHint="#105313"
        android:textColorLink="#105313"
        android:textSize="18sp"
        app:layout_constraintBottom_toTopOf="@+id/txtemail"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/txtlogin"
        tools:ignore="TextContrastCheck" />

    <EditText
        android:id="@+id/txtemail"
        android:layout_width="244dp"
        android:layout_height="55dp"
        android:layout_marginStart="101dp"
        android:layout_marginTop="6dp"
        android:layout_marginEnd="100dp"
        android:layout_marginBottom="22dp"
        android:autofillHints=""
        android:ems="10"
        android:hint="@string/txtemail"
        android:inputType="textEmailAddress"
        android:textColor="#105313"
        android:textColorHighlight="#105313"
        android:textColorHint="#105313"
        android:textColorLink="#105313"
        app:layout_constraintBottom_toTopOf="@+id/txtsenha1"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/txtnome"
        tools:ignore="TextContrastCheck" />

    <EditText
        android:id="@+id/txtsenha1"
        android:layout_width="247dp"
        android:layout_height="55dp"
        android:layout_marginStart="100dp"
        android:layout_marginTop="6dp"
        android:layout_marginEnd="100dp"
        android:layout_marginBottom="20dp"
        android:autofillHints=""
        android:ems="10"
        android:hint="@string/txtsenha1"
        android:inputType="textPassword"
        android:textColor="#105313"
        android:textColorHighlight="#105313"
        android:textColorHint="#105313"
        android:textColorLink="#105313"
        app:layout_constraintBottom_toTopOf="@+id/txtsenha2"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/txtemail" />

    <EditText
        android:id="@+id/txtsenha2"
        android:layout_width="245dp"
        android:layout_height="51dp"
        android:layout_marginStart="100dp"
        android:layout_marginTop="10dp"
        android:layout_marginEnd="100dp"
        android:layout_marginBottom="80dp"
        android:autofillHints=""
        android:ems="10"
        android:hint="@string/txtsenha2"
        android:inputType="textPassword"
        android:textColor="#105313"
        android:textColorHighlight="#105313"
        android:textColorHint="#105313"
        android:textColorLink="#105313"
        app:layout_constraintBottom_toTopOf="@+id/btnenviar"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/txtsenha1" />


        <resources>
    <string name="app_name">appteste</string>
    <string name="txtlogin">  Faça seu Login</string>
    <string name="txtnome">Insira seu nome</string>
    <string name="txtemail">Insira seu email</string>
    <string name="txtsenha1">Insira uma senha</string>
    <string name="txtsenha2">Insira a senha novamente</string>
    <string name="btnenviar">Enviar</string>
</resources>
