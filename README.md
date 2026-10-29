# Develop an Android Application Using ScrollView to Display Long Scrollable Content

**Project Name:** ScrollViewLayout

## Aim

To develop an Android application using `ScrollView` to display long, scrollable content in a Student Registration Form.

## I. Filename: `activity_main.xml`

**Location:** `app/src/main/res/layout/activity_main.xml`

```xml
<?xml version="1.0" encoding="utf-8"?>
<ScrollView
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:fillViewport="true">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical"
        android:padding="16dp">

        <!-- Heading -->
        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginBottom="20dp"
            android:gravity="center"
            android:text="Student Registration Form"
            android:textSize="24sp"
            android:textStyle="bold" />

        <!-- Full Name -->
        <EditText
            android:id="@+id/etName"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:hint="Enter Full Name"
            android:inputType="textPersonName" />

        <!-- Email -->
        <EditText
            android:id="@+id/etEmail"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:hint="Enter Email"
            android:inputType="textEmailAddress" />

        <!-- Phone Number -->
        <EditText
            android:id="@+id/etPhone"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:hint="Enter Phone Number"
            android:inputType="phone" />

        <!-- Address -->
        <EditText
            android:id="@+id/etAddress"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:hint="Enter Address"
            android:inputType="textPostalAddress" />

        <!-- City -->
        <EditText
            android:id="@+id/etCity"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:hint="Enter City"
            android:inputType="textCapWords" />

        <!-- State -->
        <EditText
            android:id="@+id/etState"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:hint="Enter State"
            android:inputType="textCapWords" />

        <!-- Country -->
        <EditText
            android:id="@+id/etCountry"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:hint="Enter Country"
            android:inputType="textCapWords" />

        <!-- Qualification -->
        <EditText
            android:id="@+id/etQualification"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:hint="Enter Qualification"
            android:inputType="textCapWords" />

        <!-- Skills -->
        <EditText
            android:id="@+id/etSkills"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:hint="Enter Skills"
            android:inputType="textMultiLine" />

        <!-- Experience -->
        <EditText
            android:id="@+id/etExperience"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:hint="Enter Experience"
            android:inputType="textMultiLine" />

        <!-- College Name -->
        <EditText
            android:id="@+id/etCollege"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:hint="Enter College Name"
            android:inputType="textCapWords" />

        <!-- Buttons -->
        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:gravity="center"
            android:orientation="horizontal">

            <Button
                android:id="@+id/btnSubmit"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Submit" />

            <Button
                android:id="@+id/btnReset"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_marginStart="16dp"
                android:text="Reset" />

        </LinearLayout>

    </LinearLayout>

</ScrollView>
```

## Explanation

1. **ScrollView:** Enables vertical scrolling when the content exceeds the screen height.
2. **LinearLayout:** Arranges all form components vertically.
3. **TextView:** Displays the heading "Student Registration Form".
4. **EditText:** Accepts the student's personal, contact, educational, and professional details.
5. **Horizontal LinearLayout:** Arranges the Submit and Reset buttons side by side.
6. **Submit Button:** Provides an interface for submitting the registration form.
7. **Reset Button:** Provides an interface for clearing the form fields.
8. **fillViewport:** Allows the scrollable content to fill the available screen height when the content is shorter than the viewport.

## Output

The application displays a Student Registration Form containing the following fields:

- Full Name
- Email
- Phone Number
- Address
- City
- State
- Country
- Qualification
- Skills
- Experience
- College Name
- Submit and Reset buttons

The user can scroll vertically to access all fields, including those below the visible screen area.

## Result

Thus, an Android application using `ScrollView` to display long, scrollable content was designed successfully.
