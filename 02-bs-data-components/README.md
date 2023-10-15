# HMTL data attributes in Bootstrap 5

Bootstrap 5 allows you to use data attributes to configure and enhance the behavior of various components and elements. Here's an example of using data attributes with a Bootstrap modal:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.5.0/dist/css/bootstrap.min.css"
      rel="stylesheet"
    />
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.5.0/dist/js/bootstrap.min.js"></script>
    <title>Bootstrap Modal with Data Attributes</title>
  </head>
  <body>
    <button
      type="button"
      class="btn btn-primary"
      data-bs-toggle="modal"
      data-bs-target="#exampleModal"
    >
      Open Modal
    </button>

    <div
      class="modal fade"
      id="exampleModal"
      tabindex="-1"
      aria-labelledby="exampleModalLabel"
      aria-hidden="true"
    >
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="modal-header">
            <h5 class="modal-title" id="exampleModalLabel">Example Modal</h5>
            <button
              type="button"
              class="btn-close"
              data-bs-dismiss="modal"
              aria-label="Close"
            ></button>
          </div>
          <div class="modal-body">
            This is an example modal with Bootstrap 5 data attributes.
          </div>
          <div class="modal-footer">
            <button
              type="button"
              class="btn btn-secondary"
              data-bs-dismiss="modal"
            >
              Close
            </button>
            <button type="button" class="btn btn-primary">Save changes</button>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>
```

In this example, we're using Bootstrap 5 data attributes like `data-bs-toggle` and `data-bs-target` to trigger a modal when the "Open Modal" button is clicked. The `data-bs-dismiss` attribute is used to close the modal when the close button is clicked. These data attributes make it easy to add interactivity to your web pages with Bootstrap 5.
