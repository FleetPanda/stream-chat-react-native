The default circle style Avatar

```js
const image =
  'https://pbs.twimg.com/profile_images/897621870069112832/dFGq6aiE_400x400.jpg';
const name = 'uthred';

<Avatar image={image} name={name} size={35} />;
```

A rounded Avatar

```js
const image =
  'https://pbs.twimg.com/profile_images/897621870069112832/dFGq6aiE_400x400.jpg';
const name = 'uthred';

<Avatar
  image={image}
  name={name}
  shape={'rounded'}
  size={35}
  style={{
    image: { extra: 'border-radius: 8px' },
    fallback: { extra: 'border-radius: 8px' },
  }}
/>;
```

And a square variation

```js
const image =
  'https://pbs.twimg.com/profile_images/897621870069112832/dFGq6aiE_400x400.jpg';
const name = 'uthred';

<Avatar
  image={image}
  name={name}
  shape={'square'}
  size={35}
  style={{
    image: { extra: 'border-radius: 0' },
    fallback: { extra: 'border-radius: 0' },
  }}
/>;
```

An example of how the fallback looks

```js
const name = 'username';

<Avatar name={name} shape={'circle'} size={35} />;
```
