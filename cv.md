**Personal information**

Name: Nikita Azizov
Phone number: +375299980786
Email: nik.azizoff2016@gmail.com
Date of birth: 23th January 2002

Information:
I want to learn js to develop beautiful and functional websites. 
I try to learn something new all the time, try myself in new directions.


**Skills**

I studied programming languages: C++, Python, Java. 
Markup languages: HTML, CSS. 
Developed games on the Unity engine.

Example of code on Java:
```
package sample;

import java.net.URL;
import java.util.ResourceBundle;
import javafx.fxml.FXML;
import javafx.scene.control.Button;
import javafx.scene.control.Label;
import javafx.scene.control.TextArea;
import javafx.scene.control.TextField;

public class Controller {

    public double x;
    public double y;
    public double z;
    public double t;

    void onClickCalculateButton(){
        try {
            x = Double.parseDouble(TextField1.getText());
            y = Double.parseDouble(TextField2.getText());
            z = Double.parseDouble(TextField3.getText());
            t = ((2 * Math.cos(x - Math.PI/6))/(0.5 + Math.sin(y) * Math.sin(y))) * (1 + ((z * z)/(3 - (z*z)/5)));
            TextArea.setText("Lab 1 10702219 Azizov\n"+"x = "+x+"\ny = "+y+"\nz = "+ z +"\nt = "+String.valueOf(t));
        }catch (Exception ex){
            TextArea.setText("Error");
        }

    }

    @FXML
    private ResourceBundle resources;

    @FXML
    private URL location;

    @FXML
    private Label Label1;

    @FXML
    private TextField TextField1;

    @FXML
    private Label Label2;

    @FXML
    private TextField TextField2;

    @FXML
    private TextField TextField3;

    @FXML
    private TextArea TextArea;

    @FXML
    private Button CalculateButton;

    @FXML
    void initialize() {
        //TextField1.setText("2")
        TextField2.setText("4");
        TextField3.setText("5");
        CalculateButton.setOnAction(event -> { onClickCalculateButton(); });
    }
}
```


**Education**

September 2019 — May 2023
Belarusian National Technical University
Software Engineer

According to the EF SET, my level of English is: B1(Intermediate)



