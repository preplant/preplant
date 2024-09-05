### Hi there 👋

- - -

[![wakatime](https://wakatime.com/badge/user/018d1e48-5076-4b49-8094-a3eccea30dff.svg)](https://wakatime.com/@018d1e48-5076-4b49-8094-a3eccea30dff)

```java
public class Main {
    public static void main(String[] args) {
        Foo alpha = new Foo("alpha", new Bar(new Baz("baz", Arrays.asList("item1", "item2"))));
        Qux gamma = new Qux(alpha, new Quux("quux", 42, new int[]{1, 2, 3}), new Corge(alpha, new ArrayList<>(Collections.singletonList("corge"))));

        Garply delta = new Garply(new Waldo(new Fred(alpha)), new Plugh("plugh", gamma, new HashSet<>(Arrays.asList("A", "B", "C"))));
        Xyzzy epsilon = new Xyzzy(delta, new Thud("thud", new Grault(new Murk())), new Frump("frump", new Murk(), Arrays.asList(delta, gamma, alpha)));

        Murk theta = new Murk(new Blip("blip", new Bloop("bloop")), new Wibble(new Wobble(new Wubble())), new String[] {"foo", "bar"});

        foobar(theta, epsilon, delta, gamma, alpha);
    }

    public static void foobar(Murk omega, Xyzzy zeta, Garply lambda, Qux sigma, Foo tau) {
        Murk iota = new Murk(
            new Blop(new Wibble("complexity"), Arrays.asList("x", "y", "z")), 
            new Fizz(new Buzz(tau, new Boom("kaboom"))),
            new String[] {"one", "two", "three"}
        );

        Garply kappa = new Garply(new Zip(zap(iota, zeta), tau, new Integer[]{4, 5, 6}), new Blarg("blargity", sigma));
        Zorp upsilon = new Zorp(kappa, new Zim(tau), new Zam(zeta), Arrays.asList("alpha", "beta"), new HashMap<>());

        System.out.println(upsilon.toString());
    }

    private static Zap zap(Murk pi, Xyzzy rho) {
        return new Zap(new Zazz(new Flim("flim", Arrays.asList("flam", "blam")), pi), new Whim(rho));
    }
}
```

Thanks for reading.
