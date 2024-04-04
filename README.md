# CodigoPAMI

<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/textViewNome"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Nome"
        android:textColor="#000205"
        android:textSize="30sp"
        app:layout_constraintBottom_toTopOf="@+id/editTextNome"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.048"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.1" />

    <EditText
        android:id="@+id/editTextNome"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:hint="Digite seu nome"
        app:layout_constraintBottom_toTopOf="@+id/textViewCpf"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textViewNome" />

    <TextView
        android:id="@+id/textViewCpf"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="CPF"
        android:textColor="#000205"
        android:textSize="30sp"
        app:layout_constraintBottom_toTopOf="@+id/editTextCpf"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.044"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/editTextNome"
        app:layout_constraintVertical_bias="0.1" />

    <EditText
        android:id="@+id/editTextCpf"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:hint="000.000.000.00"
        app:layout_constraintBottom_toTopOf="@+id/textViewDataNascimento"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textViewCpf" />

    <TextView
        android:id="@+id/textViewDataNascimento"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Data de Nascimento"
        android:textColor="#000205"
        android:textSize="30sp"
        app:layout_constraintBottom_toTopOf="@+id/editTextDataNascimento"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0444"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/editTextCpf"
        app:layout_constraintVertical_bias="0.1" />

    <EditText
        android:id="@+id/editTextDataNascimento"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:hint="00/00/00"
        app:layout_constraintBottom_toTopOf="@+id/textViewNomeMae"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textViewDataNascimento" />

    <TextView
        android:id="@+id/textViewNomeMae"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Nome da Mãe"
        android:textColor="#000205"
        android:textSize="30sp"
        app:layout_constraintBottom_toTopOf="@+id/editTextNomeMae"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0444"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/editTextDataNascimento"
        app:layout_constraintVertical_bias="0.1" />

    <EditText
        android:id="@+id/editTextNomeMae"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:hint="Digite o nome "
        app:layout_constraintBottom_toTopOf="@+id/buttonVoltar"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textViewNomeMae" />

    <Button
        android:id="@+id/buttonVoltar"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:backgroundTint="#0368ff"
        android:text="Voltar"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/editTextNomeMae"
        app:layout_constraintVertical_bias="0.1" />

    <Button
        android:id="@+id/buttonContinuar"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Continuar"
        android:backgroundTint="#0368ff"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.5"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/editTextNomeMae"
        app:layout_constraintVertical_bias="0.1" />


</androidx.constraintlayout.widget.ConstraintLayout>
