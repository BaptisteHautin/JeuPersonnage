# JeuPersonnage

Voici mon TP jeupersonnage :

package Personnage;
public class Personnage{
        public Personnage (String name, int life){
                this.nom=name;
                this.vie=life;}

        private String nom;
        private int vie;

        public String LeNom(){
                return this.nom; }

        public int LaVie(){
                return this.vie; }

        public void AugmenterVie(int aug){
                this.vie = this.vie+aug; }

        public void Attaque(Personnage perso, int force){
                perso.vie = perso.vie - force/2;
                this.vie = this.vie - force/2; }
}
