# MSSQL-ANDROID-CONNECTION-2
android mssql connection class file


Step One    : Add class 
Step Two    : implementation 'net.sourceforge.jtds:jtds:1.3.1'  // Add dependency
Step Three  : Class Function by their object 
              
              private Connection connection =null;
              try {
                    cc con = new cc();
                    connection = con.TCN();
                    textView.setHint("Enter School Code Here");
                  } 
              catch (Exception e)
              {
                    e.printStackTrace();
                    textView.setText("ERROR/FAILURE");
              }
