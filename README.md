# lab-sesi-5
package com.company;

public class Tabung
{
        double rad = 1;
        double high = 1;

        public double getVolume(){
            return Math.PI * rad * rad * high;
        }
        public double getLuasAlas(){
            return Math.PI * rad * rad;
        }
        public double setRadius(double R){
            return rad = R;
        }
        public double setTinggi(double T){
            return high = T;
        }
}
