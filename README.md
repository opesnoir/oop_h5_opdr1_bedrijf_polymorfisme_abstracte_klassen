# oop_les5_opdracht1_bedrijf_polymorfisme_abstracte_klasse
Polymorfisme, abstracte klasse,

// gebruik forloop om de items te printen
        for (int i = 0; i < personen.length; i++) {
            toonJaarInkomen(personen[i]);
        }
    }

// methode om het jaarinkomen te tonen - deze staat onder de main methode in de launcher, let op hij is void en hij gebruikt een souf
    public static void toonJaarInkomen(Persoon persoon){
        System.out.printf("%s verdient %.2f per jaar\n", persoon.getNaam(), persoon.berekenJaarInkomen());
    }

// Casten 
//aantal uren inhuur zzp'ers
((Zzper) assistent).huurIn(160); // je moet hem eerst casten naar zzper, daar staat de methode die je wil benaderen
((Zzper) projectleider).huurIn(320);