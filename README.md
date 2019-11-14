DANS MANIFEST AJOUTER CA DANS "APPLICATION"


        <activity
            android:name=".Activities.Activity_exception_handler"
            android:screenOrientation="portrait"
            android:theme="@style/AppTheme.NoActionBar"
            android:windowSoftInputMode="adjustPan"
            />
            
    CREER UNE CLASS Activity_exception_handler extends AppCompatActivity
    CREER UNE CLASS HandlerActivity extends AppCompatActivity
    CREER UNE CLASS ExceptionHandler implements java.lang.Thread.UncaughtExceptionHandler
