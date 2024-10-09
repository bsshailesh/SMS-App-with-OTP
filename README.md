Use Android Studio to compile the code.
Make sure to use the import libraries

    MySMSReceiver.java
  import android.content.BroadcastReceiver;
  import android.content.Context;
  import android.content.Intent;
  import android.os.Build;
  import android.os.Bundle;
  import android.telephony.SmsMessage;
  import android.widget.Toast;
  
    MainActivity.java
import androidx.appcompat.app.AppCompatActivity;
import androidx.core.app.ActivityCompat;
import androidx.core.content.ContextCompat;

import android.Manifest;
import android.content.pm.PackageManager;
import android.os.Bundle;
import android.widget.TextView;
import android.widget.Toast;

import com.example.SmsApp.R;

import java.text.SimpleDateFormat;
import java.util.Date;
import java.util.Locale;
