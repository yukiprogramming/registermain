# registermain

package com.example.jane.loginregister;

import android.support.v7.app.AppCompatActivity;
import android.os.Bundle;
import android.view.View;

public class Register extends AppCompatActivity implements View.OnClickListener{

    android.widget.Button bRegister;
    android.widget.EditText etName, etAge, etUsername, etPassword;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_register);

        etName = (android.widget.EditText) findViewById(R.id.etName);
        etAge = (android.widget.EditText) findViewById(R.id.etAge);
        etUsername = (android.widget.EditText) findViewById(R.id.etUsername);
        etPassword = (android.widget.EditText) findViewById(R.id.etPassword);
        bRegister = (android.widget.Button) findViewById(R.id.bRegister);

        bRegister.setOnClickListener(this);
    }

    @Override
    public void onClick(View v) {
        switch(v.getId()){
            case R.id.bRegister:



                break;
        }
    }
}
