## Card component

```jsx
import Card from './Card'

export default {
  title: 'Component/Card',
  component: Card,
}

const Template = args => <Card {...args} />

export const WithAuthor = Template.bind({})
WithAuthor.args = {
  title: 'Node.js',
  text: 'What is node.js and how to use it?',
  author: 'John Doe',
}

export const WithoutAuthor = Template.bind({})
WithoutAuthor.args = {
  title: 'Node.js',
  text: 'What is node.js and how to use it?',
}

export const WithColor = Template.bind({})
WithColor.args = {
  title: 'Node.js',
  text: 'What is node.js and how to use it?',
  color: 'hotpink',
}

export const WithoutColor = Template.bind({})
WithoutColor.args = {
  title: 'Node.js',
  text: 'What is node.js and how to use it?',
  author: 'John Doe',
}
```
