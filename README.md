# hesapmakinesi
/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/GUIForms/JFrame.java to edit this template
 */
package hesap;

/**
 *
 * @author Lenovo
 */
public class ekran extends javax.swing.JFrame {
    double NumEnter1;
    double NumEnter2;
    double Result;
    String op;
    /**
     * Creates new form ekran
     */
    public ekran() {
        initComponents();
    }

    /**
     * This method is called from within the constructor to initialize the form.
     * WARNING: Do NOT modify this code. The content of this method is always
     * regenerated by the Form Editor.
     */
    @SuppressWarnings("unchecked")
    // <editor-fold defaultstate="collapsed" desc="Generated Code">                          
    private void initComponents() {

        textField1 = new java.awt.TextField();
        jLabel1 = new javax.swing.JLabel();
        ekran = new javax.swing.JTextField();
        arti = new javax.swing.JButton();
        ac = new javax.swing.JButton();
        sekiz = new javax.swing.JButton();
        dokuz = new javax.swing.JButton();
        yedi = new javax.swing.JButton();
        alti = new javax.swing.JButton();
        dort = new javax.swing.JButton();
        eksi = new javax.swing.JButton();
        bes = new javax.swing.JButton();
        uc = new javax.swing.JButton();
        bir = new javax.swing.JButton();
        iki = new javax.swing.JButton();
        carpma = new javax.swing.JButton();
        sifir = new javax.swing.JButton();
        notlar = new javax.swing.JButton();
        bolme = new javax.swing.JButton();
        esittir = new javax.swing.JButton();

        textField1.setText("textField1");

        jLabel1.setText("Birinci Sayı");

        setDefaultCloseOperation(javax.swing.WindowConstants.EXIT_ON_CLOSE);
        setBackground(new java.awt.Color(204, 204, 255));

        ekran.setFont(new java.awt.Font("Segoe UI", 1, 24)); // NOI18N

        arti.setBackground(new java.awt.Color(255, 153, 204));
        arti.setFont(new java.awt.Font("Arial Black", 1, 36)); // NOI18N
        arti.setText("+");
        arti.setMaximumSize(new java.awt.Dimension(75, 4));
        arti.setMinimumSize(new java.awt.Dimension(75, 4));
        arti.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                artiActionPerformed(evt);
            }
        });

        ac.setBackground(new java.awt.Color(255, 153, 204));
        ac.setFont(new java.awt.Font("Arial Black", 1, 24)); // NOI18N
        ac.setText("C");
        ac.setMaximumSize(new java.awt.Dimension(75, 4));
        ac.setMinimumSize(new java.awt.Dimension(75, 4));
        ac.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                acActionPerformed(evt);
            }
        });

        sekiz.setBackground(new java.awt.Color(255, 153, 204));
        sekiz.setFont(new java.awt.Font("Arial Black", 1, 24)); // NOI18N
        sekiz.setText("8");
        sekiz.setMaximumSize(new java.awt.Dimension(75, 4));
        sekiz.setMinimumSize(new java.awt.Dimension(75, 4));
        sekiz.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                sekizActionPerformed(evt);
            }
        });

        dokuz.setBackground(new java.awt.Color(255, 153, 204));
        dokuz.setFont(new java.awt.Font("Arial Black", 1, 24)); // NOI18N
        dokuz.setText("9");
        dokuz.setMaximumSize(new java.awt.Dimension(75, 4));
        dokuz.setMinimumSize(new java.awt.Dimension(75, 4));
        dokuz.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                dokuzActionPerformed(evt);
            }
        });

        yedi.setBackground(new java.awt.Color(255, 153, 204));
        yedi.setFont(new java.awt.Font("Arial Black", 1, 24)); // NOI18N
        yedi.setText("7");
        yedi.setMaximumSize(new java.awt.Dimension(75, 4));
        yedi.setMinimumSize(new java.awt.Dimension(75, 4));
        yedi.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                yediActionPerformed(evt);
            }
        });

        alti.setBackground(new java.awt.Color(255, 153, 204));
        alti.setFont(new java.awt.Font("Arial Black", 1, 24)); // NOI18N
        alti.setText("6");
        alti.setMaximumSize(new java.awt.Dimension(75, 4));
        alti.setMinimumSize(new java.awt.Dimension(75, 4));
        alti.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                altiActionPerformed(evt);
            }
        });

        dort.setBackground(new java.awt.Color(255, 153, 204));
        dort.setFont(new java.awt.Font("Arial Black", 1, 24)); // NOI18N
        dort.setText("4");
        dort.setMaximumSize(new java.awt.Dimension(75, 4));
        dort.setMinimumSize(new java.awt.Dimension(75, 4));
        dort.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                dortActionPerformed(evt);
            }
        });

        eksi.setBackground(new java.awt.Color(255, 153, 204));
        eksi.setFont(new java.awt.Font("Arial Black", 1, 36)); // NOI18N
        eksi.setText("-");
        eksi.setMaximumSize(new java.awt.Dimension(75, 4));
        eksi.setMinimumSize(new java.awt.Dimension(75, 4));
        eksi.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                eksiActionPerformed(evt);
            }
        });

        bes.setBackground(new java.awt.Color(255, 153, 204));
        bes.setFont(new java.awt.Font("Arial Black", 1, 24)); // NOI18N
        bes.setText("5");
        bes.setMaximumSize(new java.awt.Dimension(75, 4));
        bes.setMinimumSize(new java.awt.Dimension(75, 4));
        bes.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                besActionPerformed(evt);
            }
        });

        uc.setBackground(new java.awt.Color(255, 153, 204));
        uc.setFont(new java.awt.Font("Arial Black", 1, 24)); // NOI18N
        uc.setText("3");
        uc.setMaximumSize(new java.awt.Dimension(75, 4));
        uc.setMinimumSize(new java.awt.Dimension(75, 4));
        uc.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                ucActionPerformed(evt);
            }
        });

        bir.setBackground(new java.awt.Color(255, 153, 204));
        bir.setFont(new java.awt.Font("Arial Black", 1, 24)); // NOI18N
        bir.setText("1");
        bir.setMaximumSize(new java.awt.Dimension(75, 4));
        bir.setMinimumSize(new java.awt.Dimension(75, 4));
        bir.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                birActionPerformed(evt);
            }
        });

        iki.setBackground(new java.awt.Color(255, 153, 204));
        iki.setFont(new java.awt.Font("Arial Black", 1, 24)); // NOI18N
        iki.setText("2");
        iki.setMaximumSize(new java.awt.Dimension(75, 4));
        iki.setMinimumSize(new java.awt.Dimension(75, 4));
        iki.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                ikiActionPerformed(evt);
            }
        });

        carpma.setBackground(new java.awt.Color(255, 153, 204));
        carpma.setFont(new java.awt.Font("Arial Black", 1, 36)); // NOI18N
        carpma.setText("*");
        carpma.setMaximumSize(new java.awt.Dimension(75, 4));
        carpma.setMinimumSize(new java.awt.Dimension(75, 4));
        carpma.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                carpmaActionPerformed(evt);
            }
        });

        sifir.setBackground(new java.awt.Color(255, 153, 204));
        sifir.setFont(new java.awt.Font("Arial Black", 1, 24)); // NOI18N
        sifir.setText("0");
        sifir.setMaximumSize(new java.awt.Dimension(75, 4));
        sifir.setMinimumSize(new java.awt.Dimension(75, 4));
        sifir.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                sifirActionPerformed(evt);
            }
        });

        notlar.setBackground(new java.awt.Color(255, 153, 204));
        notlar.setFont(new java.awt.Font("Arial Black", 1, 24)); // NOI18N
        notlar.setText(".");
        notlar.setMaximumSize(new java.awt.Dimension(75, 4));
        notlar.setMinimumSize(new java.awt.Dimension(75, 4));
        notlar.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                notlarActionPerformed(evt);
            }
        });

        bolme.setBackground(new java.awt.Color(255, 153, 204));
        bolme.setFont(new java.awt.Font("Arial Black", 1, 36)); // NOI18N
        bolme.setText("/");
        bolme.setMaximumSize(new java.awt.Dimension(75, 4));
        bolme.setMinimumSize(new java.awt.Dimension(75, 4));
        bolme.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                bolmeActionPerformed(evt);
            }
        });

        esittir.setBackground(new java.awt.Color(255, 153, 204));
        esittir.setFont(new java.awt.Font("Arial Black", 1, 24)); // NOI18N
        esittir.setText("=");
        esittir.setMaximumSize(new java.awt.Dimension(75, 4));
        esittir.setMinimumSize(new java.awt.Dimension(75, 4));
        esittir.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                esittirActionPerformed(evt);
            }
        });

        javax.swing.GroupLayout layout = new javax.swing.GroupLayout(getContentPane());
        getContentPane().setLayout(layout);
        layout.setHorizontalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(layout.createSequentialGroup()
                .addGap(29, 29, 29)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(layout.createSequentialGroup()
                        .addComponent(ekran, javax.swing.GroupLayout.PREFERRED_SIZE, 423, javax.swing.GroupLayout.PREFERRED_SIZE)
                        .addContainerGap(javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))
                    .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, layout.createSequentialGroup()
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.TRAILING)
                            .addComponent(ac, javax.swing.GroupLayout.Alignment.LEADING, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                            .addGroup(javax.swing.GroupLayout.Alignment.LEADING, layout.createSequentialGroup()
                                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false)
                                    .addComponent(yedi, javax.swing.GroupLayout.PREFERRED_SIZE, 70, javax.swing.GroupLayout.PREFERRED_SIZE)
                                    .addComponent(dort, javax.swing.GroupLayout.PREFERRED_SIZE, 70, javax.swing.GroupLayout.PREFERRED_SIZE)
                                    .addComponent(bir, javax.swing.GroupLayout.PREFERRED_SIZE, 70, javax.swing.GroupLayout.PREFERRED_SIZE)
                                    .addComponent(sifir, javax.swing.GroupLayout.PREFERRED_SIZE, 70, javax.swing.GroupLayout.PREFERRED_SIZE))
                                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                                    .addComponent(sekiz, javax.swing.GroupLayout.PREFERRED_SIZE, 70, javax.swing.GroupLayout.PREFERRED_SIZE)
                                    .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.TRAILING, false)
                                        .addComponent(iki, javax.swing.GroupLayout.PREFERRED_SIZE, 70, javax.swing.GroupLayout.PREFERRED_SIZE)
                                        .addComponent(notlar, javax.swing.GroupLayout.PREFERRED_SIZE, 70, javax.swing.GroupLayout.PREFERRED_SIZE)
                                        .addComponent(bes, javax.swing.GroupLayout.PREFERRED_SIZE, 70, javax.swing.GroupLayout.PREFERRED_SIZE)))
                                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                                    .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                                        .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, layout.createParallelGroup(javax.swing.GroupLayout.Alignment.TRAILING, false)
                                            .addComponent(dokuz, javax.swing.GroupLayout.Alignment.LEADING, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                                            .addComponent(alti, javax.swing.GroupLayout.Alignment.LEADING, javax.swing.GroupLayout.PREFERRED_SIZE, 75, javax.swing.GroupLayout.PREFERRED_SIZE))
                                        .addComponent(uc, javax.swing.GroupLayout.PREFERRED_SIZE, 75, javax.swing.GroupLayout.PREFERRED_SIZE))
                                    .addComponent(esittir, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                                .addGap(40, 40, 40)
                                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.TRAILING, false)
                                    .addComponent(bolme, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                                    .addComponent(carpma, javax.swing.GroupLayout.Alignment.LEADING, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                                    .addComponent(arti, javax.swing.GroupLayout.Alignment.LEADING, javax.swing.GroupLayout.DEFAULT_SIZE, 75, Short.MAX_VALUE)
                                    .addComponent(eksi, javax.swing.GroupLayout.Alignment.LEADING, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))))
                        .addGap(80, 80, 80))))
        );
        layout.setVerticalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, layout.createSequentialGroup()
                .addGap(23, 23, 23)
                .addComponent(ekran, javax.swing.GroupLayout.PREFERRED_SIZE, 48, javax.swing.GroupLayout.PREFERRED_SIZE)
                .addGap(25, 25, 25)
                .addComponent(ac, javax.swing.GroupLayout.PREFERRED_SIZE, 70, javax.swing.GroupLayout.PREFERRED_SIZE)
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                        .addComponent(yedi, javax.swing.GroupLayout.Alignment.TRAILING, javax.swing.GroupLayout.PREFERRED_SIZE, 70, javax.swing.GroupLayout.PREFERRED_SIZE)
                        .addComponent(sekiz, javax.swing.GroupLayout.Alignment.TRAILING, javax.swing.GroupLayout.PREFERRED_SIZE, 70, javax.swing.GroupLayout.PREFERRED_SIZE))
                    .addComponent(dokuz, javax.swing.GroupLayout.Alignment.TRAILING, javax.swing.GroupLayout.PREFERRED_SIZE, 70, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(arti, javax.swing.GroupLayout.Alignment.TRAILING, javax.swing.GroupLayout.PREFERRED_SIZE, 70, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addGap(18, 18, 18)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addComponent(bes, javax.swing.GroupLayout.PREFERRED_SIZE, 70, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(dort, javax.swing.GroupLayout.PREFERRED_SIZE, 70, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(alti, javax.swing.GroupLayout.PREFERRED_SIZE, 70, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(eksi, javax.swing.GroupLayout.PREFERRED_SIZE, 70, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addComponent(uc, javax.swing.GroupLayout.PREFERRED_SIZE, 70, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(carpma, javax.swing.GroupLayout.PREFERRED_SIZE, 70, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(bir, javax.swing.GroupLayout.Alignment.TRAILING, javax.swing.GroupLayout.PREFERRED_SIZE, 70, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(iki, javax.swing.GroupLayout.Alignment.TRAILING, javax.swing.GroupLayout.PREFERRED_SIZE, 70, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.TRAILING)
                    .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false)
                        .addComponent(sifir, javax.swing.GroupLayout.PREFERRED_SIZE, 70, javax.swing.GroupLayout.PREFERRED_SIZE)
                        .addComponent(notlar, javax.swing.GroupLayout.PREFERRED_SIZE, 70, javax.swing.GroupLayout.PREFERRED_SIZE)
                        .addComponent(esittir, javax.swing.GroupLayout.PREFERRED_SIZE, 70, javax.swing.GroupLayout.PREFERRED_SIZE))
                    .addComponent(bolme, javax.swing.GroupLayout.PREFERRED_SIZE, 70, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addContainerGap(54, Short.MAX_VALUE))
        );

        pack();
    }// </editor-fold>                        
    private void ekranaYaz(String q)
    {
        String Nums = ekran.getText() + q;
        ekran.setText(Nums);
    }
    private void artiActionPerformed(java.awt.event.ActionEvent evt) {                                     
        // TODO add your handling code here:
        NumEnter1 = Double.parseDouble(ekran.getText());
        ekran.setText("");
        op ="+";
    }                                    

    private void sifirActionPerformed(java.awt.event.ActionEvent evt) {                                      
        // TODO add your handling code here:
        ekranaYaz("0");
    }                                     

    private void bolmeActionPerformed(java.awt.event.ActionEvent evt) {                                      
        // TODO add your handling code here:
        NumEnter1= Double.parseDouble(ekran.getText());
        ekran.setText("");
        op ="/";
    }                                     

    private void birActionPerformed(java.awt.event.ActionEvent evt) {                                    
        // TODO add your handling code here:
        ekranaYaz("1");
    }                                   

    private void notlarActionPerformed(java.awt.event.ActionEvent evt) {                                       
        // TODO add your handling code here:
        if (! ekran.getText(). contains("."))
        {
            ekran.setText(ekran.getText() + notlar.getText());
        }
    }                                      

    private void eksiActionPerformed(java.awt.event.ActionEvent evt) {                                     
        // TODO add your handling code here:
        NumEnter1 = Double.parseDouble(ekran.getText());
        ekran.setText("");
        op ="-";
    }                                    

    private void carpmaActionPerformed(java.awt.event.ActionEvent evt) {                                       
        // TODO add your handling code here:
        NumEnter1 = Double.parseDouble(ekran.getText());
        ekran.setText("");
        op ="*";
    }                                      

    private void esittirActionPerformed(java.awt.event.ActionEvent evt) {                                        
        // TODO add your handling code here:
        NumEnter2 = Double.parseDouble(ekran.getText());
        if (op == "+")
        {
            Result = NumEnter1 + NumEnter2;
            ekran.setText(String.valueOf(Result));
        }
        else if (op == "-")
        {  
            Result = NumEnter1 - NumEnter2;
            ekran.setText(String.valueOf(Result));   
        }
        else if (op == "*")
        {  
            Result = NumEnter1 * NumEnter2;
            ekran.setText(String.valueOf(Result));   
        }
         else if (op == "/")
        {  
            Result = NumEnter1 / NumEnter2;
            ekran.setText(String.valueOf(Result));   
        }   
    }                                       

    private void ikiActionPerformed(java.awt.event.ActionEvent evt) {                                    
        // TODO add your handling code here:
        ekranaYaz("2");
    }                                   

    private void ucActionPerformed(java.awt.event.ActionEvent evt) {                                   
        // TODO add your handling code here:
        ekranaYaz("3");
    }                                  

    private void dortActionPerformed(java.awt.event.ActionEvent evt) {                                     
        // TODO add your handling code here:
        ekranaYaz("4");
    }                                    

    private void besActionPerformed(java.awt.event.ActionEvent evt) {                                    
        // TODO add your handling code here:
        ekranaYaz("5");
    }                                   

    private void altiActionPerformed(java.awt.event.ActionEvent evt) {                                     
        // TODO add your handling code here:
        ekranaYaz("6");
    }                                    

    private void yediActionPerformed(java.awt.event.ActionEvent evt) {                                     
        // TODO add your handling code here:
        ekranaYaz("7");
    }                                    

    private void sekizActionPerformed(java.awt.event.ActionEvent evt) {                                      
        // TODO add your handling code here:
        ekranaYaz("8");
    }                                     

    private void dokuzActionPerformed(java.awt.event.ActionEvent evt) {                                      
        // TODO add your handling code here:
        ekranaYaz("9");
    }                                     

    private void acActionPerformed(java.awt.event.ActionEvent evt) {                                   
        // TODO add your handling code here:
        ekran.setText("");
    }                                  

    /**
     * @param args the command line arguments
     */
    public static void main(String args[]) {
        /* Set the Nimbus look and feel */
        //<editor-fold defaultstate="collapsed" desc=" Look and feel setting code (optional) ">
        /* If Nimbus (introduced in Java SE 6) is not available, stay with the default look and feel.
         * For details see http://download.oracle.com/javase/tutorial/uiswing/lookandfeel/plaf.html 
         */
        try {
            for (javax.swing.UIManager.LookAndFeelInfo info : javax.swing.UIManager.getInstalledLookAndFeels()) {
                if ("Nimbus".equals(info.getName())) {
                    javax.swing.UIManager.setLookAndFeel(info.getClassName());
                    break;
                }
            }
        } catch (ClassNotFoundException ex) {
            java.util.logging.Logger.getLogger(ekran.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (InstantiationException ex) {
            java.util.logging.Logger.getLogger(ekran.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (IllegalAccessException ex) {
            java.util.logging.Logger.getLogger(ekran.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (javax.swing.UnsupportedLookAndFeelException ex) {
            java.util.logging.Logger.getLogger(ekran.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        }
        //</editor-fold>

        /* Create and display the form */
        java.awt.EventQueue.invokeLater(new Runnable() {
            public void run() {
                new ekran().setVisible(true);
            }
        });
    }

    // Variables declaration - do not modify                     
    private javax.swing.JButton ac;
    private javax.swing.JButton alti;
    private javax.swing.JButton arti;
    private javax.swing.JButton bes;
    private javax.swing.JButton bir;
    private javax.swing.JButton bolme;
    private javax.swing.JButton carpma;
    private javax.swing.JButton dokuz;
    private javax.swing.JButton dort;
    private javax.swing.JTextField ekran;
    private javax.swing.JButton eksi;
    private javax.swing.JButton esittir;
    private javax.swing.JButton iki;
    private javax.swing.JLabel jLabel1;
    private javax.swing.JButton notlar;
    private javax.swing.JButton sekiz;
    private javax.swing.JButton sifir;
    private java.awt.TextField textField1;
    private javax.swing.JButton uc;
    private javax.swing.JButton yedi;
    // End of variables declaration                   
}

