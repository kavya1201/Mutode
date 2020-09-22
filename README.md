
Mutation testing for Node.js and JavaScript.

**Mutode** generates mutants (small changes of code) and runs your tests. If the tests fail, it means the mutant was detected and **killed**; if your tests pass, it means the mutant **survived** and your tests can be improved.

## Install

**Requires Node 8+**

Globally:

```sh
npm i -g mutode
```

Locally as a dev dependency:

```sh
npm i -D mutode
```

## Use

Globally:

```sh
mutode [options] [paths]
```

Locally with `npx`:

```sh
npx mutode [options] [paths]
```

Locally with a package.json script:

```
{
  ...
  "scripts": {
    "test: "my test command",
    "mutode": "mutode [options] [paths]"
  }
  ...
}
```


