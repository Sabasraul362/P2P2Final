private void jButton1ActionPerformed(java.awt.event.ActionEvent evt) {                                         
      int num1;
      int num2;
      int suma=0;
      int resta=0;
      float div=0;
      
      num1=Integer.parseInt(this.txtnum1.getText());
      num2=Integer.parseInt(this.txtnum2.getText());
      
      suma=num1+num2;
      txtsumar.setText(String.valueOf(suma));
      resta=num1-num2;
      txtrestar.setText(String.valueOf(resta));
      mult=num1*num2;
            
    }

public Principal() {
        initComponents();
        add(new PanelPrincipal());
        setSize(800, 400);

    }
