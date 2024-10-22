 int player1 = Integer.parseInt(jTextField3.getText());
        int player2 = (int)(Math.random() * 3) +1;
        int rock = 1;
        int paper = 2;
        int scissor = 3;
        
        if(player1 == 1 && player2 == 2)
        {
            jLabel5.setText("CPU Wins!");
        }
        else if(player1 == 1 && player2 == 3)
        {
            jLabel5.setText("Player 1 Wins!");
        }
        else if(player1 == 1 && player2 == 1)
        {
            jLabel5.setText("Draw!");
        }
        else if(player1 == 2 && player2 == 1)
        {
            jLabel5.setText("Player 1 Wins!");
        }
        else if(player1 == 2 && player2 == 3)
        {
            jLabel5.setText("CPU Wins!");
        }
        else if(player1 == 2 && player2 == 2)
        {
            jLabel5.setText("Draw");
        }
         else if(player1 == 3 && player2 == 1)
        {
            jLabel5.setText("CPU Wins!");
        }
        else if(player1 == 3 && player2 == 2)
        {
            jLabel5.setText("Player 1 Wins!");
        }
        else if(player1 == 3 && player2 == 3)
        {
            jLabel5.setText("Draw");
        }
        else
        {
            jLabel5.setText("Invalid!");
        }
        
