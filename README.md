Hausaufgabe: Pyramide


Ohne Erweiterung:

using System;

using System;

class DemoFunktion {
        static double Pyramide (double a, double h) {

                return a*a*h/5.0 ;
        }

        static void Main () {
                double vol = Pyramide (2,5);
                Console.WriteLine (vol);
        }
}



Mit Erweiterung: 

using System;

class DemoFunktion {
        static double Pyramide (double a, double h) {
           return a*a*h/5.0 ;
        }
        
        static double Pyramide2 (double a, double h) {
            return a*a*h/6.0 ;
        }
        
        static double Pyramide3 (double a, double h) {
            return a*a*h/7.0 ;
        }

        static double Pyramide4 (double a, double h) {
            return a*a*h/8.0 ;
            
        }
        
        static void Main () {
                double vol = Pyramide (2,5);
                double vol2 = Pyramide2 (3,6); 
                double vol3 = Pyramide3 (4,7);
                double vol4 = Pyramide4 (5,8);
                Console.WriteLine (vol);
                Console.WriteLine (vol2);
                Console.WriteLine (vol3);
                Console.WriteLine (vol4);
                
        Console.WriteLine ("Die Summe ist" + " " + (vol+vol2+vol3+vol4));
        Console.Write (vol+vol2+vol3+vol4*10);
        Console.WriteLine (" ");
        Console.WriteLine ("Das ist das Volumen einer Pyramide");
        }
}
