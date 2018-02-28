/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package shapdrawingpplet;

/**
 *
 * @author sierraamador
 */

import java.awt.Color;
import javax.swing.JApplet;
import java.awt.Graphics;

public class ShapDrawingApplet extends JApplet
{
    public void paint ( Graphics g )
    {
     super.paint( g );
 
//circle1     
int centerX = 250, centerY = 225;
int radius = 25;

//Circle1
g.setColor(Color.red);
g.fillOval( centerX - radius, centerY - radius, radius * 2, radius * 2);

//Circle2
g.setColor(Color.black);
g.fillOval( 270 - radius, centerY - radius, radius * 2, radius * 2);

//circle 3
g.setColor(Color.red);
g.fillOval( 290 - radius, centerY - radius, radius * 2, radius * 2);

//circle4
g.setColor(Color.black);
g.fillOval( 310 - radius, centerY - radius, radius * 2 , radius * 2);

//writing
g.setColor(Color.black);
g.drawString("Sierra Amador", 250 , 190);
    }
    
}
