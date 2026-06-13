# Short Response Questions

Answer the following questions in your own words. Each response should be 2-4 sentences.

## Question 1: Accessibility

What is accessibility and why does it matter? Name at least two ways that labels make our form inputs more accessible?

**Your Answer:**

Accessibility means building your website so that everyone, including people with disabilities or those using screen readers, can navigate and use it easily. Form labels make inputs accessible because screen readers will read the label aloud when a user focuses on the input box. Plus, clicking the label automatically focuses or selects the input field, which gives people a much larger target area to click.

## Question 2: The `name` vs `id` Attribute

`for`, `name` and `id` are attributes we put on form labels and inputs, but they serve different purposes. Explain what each attribute is used for.

**Your Answer:**

The `id` is a unique identifier on an input that lets you target it with CSS, JavaScript, or a label's `for` attributes to link them together. The `for` attribute goes on a `<label>` and matches an input's `id` so clicking the label focuses that specific input. The `name` attribute is totally different—it acts as the key for the data when the form gets submitted to a server.

## Question 3: Input Types

Why do we use specific input types like `type="email"` or `type="number"` instead of just using `type="text"` for everything? What advantages do they provide?

**Your Answer:**

Using specific input types triggers built-in browser validation, like making sure an email address actually has an `@` symbol before letting the form submit. It also massively improves user experience, especially on mobile devices where `type="number"` will automatically open up a numeric keypad instead of a regular keyboard.

## Question 4: Form Submission

Form data is typically sent to a server (a computer that receives the data and does something with it). Provide an example of a real web application that uses a form and, to the best of your ability, explain what the application does with that form data.

**Your Answer:**
When you create a new post on an app like twitter or instagram, you're filling out a form with your text, tags, or images. When you hit submit, the application sends that data to their backend server, which processes it, assigns it to your account profile, and saves it into a database. Then, the server updates everyone's feeds so your friends can see what you posted.
