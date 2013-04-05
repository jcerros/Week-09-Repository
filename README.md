Week-09-Repository
==================

tic tac toe game

import javax.swing.JOptionPane;
import java.util.Scanner;
public class TICTACTOE{
 public static void main(String args[]){
  boolean bPlaying= false;
  
  String sBoard = "";
  String cell1 ="1", cell2="2", cell3 = "3", cell4="4",
    cell5 ="5", cell6="6", cell7 = "7", cell8="8",
    cell9 ="9";
  String susermove;
  boolean bInvalidMove= false;
   Scanner Ozil= new Scanner(System.in);
  
 // loop till game is over
  do{
   bInvalidMove= true;
   // loop till valid move
  do{
   sBoard = cell1+"|"+cell2+"|"+cell3+"\n";
   sBoard = sBoard + "--|--|--\n";
   sBoard = sBoard+ cell4+"|"+cell5+"|"+cell6+"\n";
   sBoard = sBoard + "--|--|--"+"\n";
   sBoard = sBoard+cell7+"|"+cell8+"|"+cell9+"\n" ;
   sBoard = sBoard+"Choose Number of a cell (Between 1-9):";
   susermove =JOptionPane.showInputDialog(null,sBoard);
  
   if (susermove.equalsIgnoreCase("1")) 
    {
    
     if (  ! cell1.equalsIgnoreCase("1"))
		   JOptionPane.showMessageDialog(null, "INVALID!\nSelect Different Move");
	   else
		   cell1 = "X";
    
    }
   
  else if(susermove.equalsIgnoreCase("2"))
    {
    
	  if ( ! cell2.equalsIgnoreCase("2"))
		  JOptionPane.showMessageDialog(null, "INVALID!\nSelect Different Move");
    else
    		cell2 = "X";
    
    }
  else if(susermove.equalsIgnoreCase("3")) 
   {
   
	  if ( ! cell3.equalsIgnoreCase("3"))
		  JOptionPane.showMessageDialog(null, "INVALID!\nSelect Different Move");
	  else
		  	cell3 = "X";
   
   }
  else if(susermove.equalsIgnoreCase("4"))
  {
   
	  if ( ! cell4.equalsIgnoreCase("4"))
		  JOptionPane.showMessageDialog(null, "INVALID!\nSelect Different Move");
	  else
		  cell4 = "X";
    }
  else if(susermove.equalsIgnoreCase("5"))
  {
	  if ( ! cell5.equalsIgnoreCase("5"))
		  JOptionPane.showMessageDialog(null, "INVALID!\nSelect Different Move");
	  else
		  cell5 = "X";
    }
   
  else if(susermove.equalsIgnoreCase("6")) 
  {
	  if ( ! cell6.equalsIgnoreCase("6"))
		  JOptionPane.showMessageDialog(null, "INVALID!\nSelect Different Move");
	  else
		  cell6 = "X";
   }
   
  else if(susermove.equalsIgnoreCase("7")) 
  {
   
	  if ( ! cell7.equalsIgnoreCase("7"))
		  JOptionPane.showMessageDialog(null, "INVALID!\nSelect Different Move");
	  else
		  cell7 = "X";
   
   }
  else if(susermove.equalsIgnoreCase("8")) 
{
    
    if (! cell8.equalsIgnoreCase("8"))
    	JOptionPane.showMessageDialog(null, "INVALID!\nSelect Different Move");
    else
    	cell8 = "X";
    }
	if (susermove.equalsIgnoreCase("9"))
   {
	   if ( ! cell9.equalsIgnoreCase("9"))
		   JOptionPane.showMessageDialog(null, "INVALID!\nSelect Different Move");
	   else
		   	cell9 = "X";
   
   }
   
   
  }while(bInvalidMove);
   
   
   
   
  
   
   
   //JOptionPane.showMessageDialog(null,sBoard);
   //sBoard = "process: a)validate input";
   //JOptionPane.showMessageDialog(null,sBoard);
   //sBoard = "process b)validate available slot";
   //JOptionPane.showMessageDialog(null,sBoard);
   //sBoard = "rebuild board";
   //JOptionPane.showMessageDialog(null,sBoard);
   //sBoard = "check winner";
   //JOptionPane.showMessageDialog(null,sBoard);
   //sBoard = "generate system move a)1-9";
   //JOptionPane.showMessageDialog(null,sBoard);
   //sBoard = "processing validate available slot";
   //JOptionPane.showMessageDialog(null,sBoard);
   //sBoard = "check winner";
   //JOptionPane.showMessageDialog(null,sBoard);
   
  }while(bPlaying=false)
   ;
  
 }
}
