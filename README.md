

PROJECT URL : https://mytechera007.ccbp.tech/

### Design Files

<details>

<summary>Click to view</summary>

- Home Route

  - [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Courses Success](https://assets.ccbp.in/frontend/content/react-js/tech-era-home-success-lg-output.png)
  - [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Courses Failure](https://assets.ccbp.in/frontend/content/react-js/tech-era-home-failure-lg-output.png)

- Course Item Details Route

  - [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Course Details Success](https://assets.ccbp.in/frontend/content/react-js/tech-era-course-details-success-lg-output.png)
  - [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Course Details Failure](https://assets.ccbp.in/frontend/content/react-js/tech-era-course-details-failure-lg-output.png)

- Not Found Route

  - [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px)](https://assets.ccbp.in/frontend/content/react-js/tech-era-page-not-found-lg-output.png)

</details>

### Set Up Instructions

<details>

<summary>Click to view</summary>

- Download dependencies by running `npm install`
- Start up the app using `npm start`

</details>

### Completion Instructions

<details>


<details>

<summary>API Requests & Responses</summary>

<br/>

**coursesApiUrl**

#### API: `https://apis.ccbp.in/te/courses`

#### Method: `GET`

#### Description:

Returns a response containing the list of all courses

#### Response:

```json
{
  "courses": [
      {
        "id": "736d1108-d98b-482f-bfd6-234498c3571f",
        "name": "HTML",
        "logo_url": "https://assets.ccbp.in/frontend/react-js/tech-era/html-logo-img.png"
      },
       ...
  ],
  "total": 16
}
```

**courseDetailsApiUrl**

#### API: `https://apis.ccbp.in/te/courses/:id`

#### Method: `GET`

#### Description:

Returns a response containing details of the course

#### Response:

```json
{
  "course_details": {
    "id": "736d1108-d98b-482f-bfd6-234498c3571f",
    "name": "HTML",
    "image_url": "https://assets.ccbp.in/frontend/react-js/tech-era/html-img.png",
    "description": "The HyperText Markup Language or HTML is the standard markup language for documents designed to be displayed in a web browser. It can be assisted by technologies such as Cascading Style Sheets (CSS) and scripting languages such as JavaScript. Web browsers receive HTML documents from a web server or local storage and render the documents into multimedia web pages."
  }
}
```

</details>



### Resources

<details>

<summary>Image URLs</summary>

- https://assets.ccbp.in/frontend/react-js/tech-era/website-logo-img.png alt should be **website logo**
- https://assets.ccbp.in/frontend/react-js/tech-era/failure-img.png alt should be **failure view**
- https://assets.ccbp.in/frontend/react-js/tech-era/not-found-img.png alt should be **not found**

</details>

<details>

<summary>Colors</summary>

<br/>

<div style="background-color:#f1f5f9; width: 150px; padding: 10px; color: black">Hex: #f1f5f9</div>
<div style="background-color:#1e293b; width: 150px; padding: 10px; color: white">Hex: #1e293b</div>
<div style="background-color:#475569; width: 150px; padding: 10px; color: white">Hex: #475569</div>
<div style="background-color:#ffffff; width: 150px; padding: 10px; color: black">Hex: #ffffff</div>
<div style="background-color:#4656a1; width: 150px; padding: 10px; color: white">Hex: #4656a1</div>
<div style="background-color:#64748b; width: 150px; padding: 10px; color: white">Hex: #64748b</div>
<div style="background-color:#e8e8e8; width: 150px; padding: 10px; color: black">Hex: #e8e8e8</div>

</details>

<details>

<summary>Font-families</summary>

- Roboto

</details>

> ### _Things to Keep in Mind_
>
> - All components you implement should go in the `src/components` directory.
