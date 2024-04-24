public class Main {
    public static void main(String[] args) {
        // Création d'une commande de café avec lait et sucre en utilisant le builder
        CoffeeOrder coffeeOrder1 = new CoffeeOrderBuilder("Espresso")
                                    .withMilk(true)
                                    .withSugar(true)
                                    .build();

        // Création d'une autre commande de café sans lait et avec sucre
        CoffeeOrder coffeeOrder2 = new CoffeeOrderBuilder("Cappuccino")
                                    .withSugar(true)
                                    .build();

        // Affichage des détails des commandes de café créées
        System.out.println("Commande 1:");
        displayCoffeeOrderDetails(coffeeOrder1);

        System.out.println("\nCommande 2:");
        displayCoffeeOrderDetails(coffeeOrder2);
    }

    // Méthode pour afficher les détails d'une commande de café
    private static void displayCoffeeOrderDetails(CoffeeOrder coffeeOrder) {
        System.out.println("Type de café: " + coffeeOrder.getCoffeeType());
        System.out.println("Avec lait: " + coffeeOrder.isWithMilk());
        System.out.println("Avec sucre: " + coffeeOrder.isWithSugar());
        // Ajoutez l'affichage d'autres options de la commande de café au besoin
    }
}
