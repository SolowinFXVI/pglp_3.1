## 3.1
1. Il y a deux responsabilités dans la classe, il y a donc un viol de SRP.
2. Si la méthode de calcul change on doit recompiler tous les programmes qui dépendent.
3. SRP n'est toujours pas respecté.Mais en ne dépendant plus de l'affichage on fix le DIP.
4. On va créer d'autres classes chacunes avec une responsabilité unique.

```JAVA
public abstract class allemploye{
    public abstract double salaire();
}

class employe1{
    private string name;
    public double calculsaliare();
}

class employe2{
    private string name;
    public void affichage();
}
```
