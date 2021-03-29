# PBOFS112B-2014436267-Latihan54

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */

/**
 *
 * @author ASUS
 *Nama      : Caterina Vinanti
 *Kelas     : PBO FS112B
 *NIM       : 2014436267
 *Deskripsi Program : Program ini berisi tentang pemrograman Koordinat
 */
class Koordinat {
    int x;
    int y;
    
    Koordinat(int x, int y) {
        setX(x);
        setY(y);
    }
    
    int getX() {
        return this.x;
    }
    
    void setX(int x) {
        this.x = x;
    }
    
    int getY() {
        return this.y;
    }
    
    void setY(int y) {
        this.y = y;
    }
}

class WarnaKoordinat {
    String namaWarna;
    
    WarnaKoordinat(int x, int y, String namaWarna) {
        setNamaWarna(namaWarna);
    }
    
    String getNamaWarna() {
        return this.namaWarna;
    }
    
    void setNamaWarna(String namaWarna) {
        this.namaWarna = namaWarna;
    }
}

/**
 *
 * @author eLx
 */
public class PBOFS112B_201446267_Latihan54_Koordinat {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        Koordinat koordinat = new Koordinat(10, 4);
        WarnaKoordinat warna = new WarnaKoordinat(koordinat.getX(), koordinat.getY(), "Jingga");
        
        System.out.println("Warna Koordinat : " + warna.getNamaWarna());
        System.out.println("Koordinat Sumbu x : " + koordinat.getX() + ", y : " + koordinat.getY());
    }
    
}

