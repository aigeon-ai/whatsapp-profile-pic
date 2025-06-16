# WhatsApp Profile Pic MCP Server

## Overview

The WhatsApp Profile Pic MCP Server is a cloud-based service that allows developers and businesses to retrieve the profile picture of any phone number registered on WhatsApp. It provides a straightforward and efficient method to enrich customer data, personalize user experiences, and enhance engagement by fetching and downloading profile pictures from WhatsApp.

## Features

- **Real-time Processing**: Quickly fetch profile pictures associated with WhatsApp numbers for real-time applications like customer onboarding, marketing, and social media platforms.
- **GDPR Compliance**: The service is designed with privacy and security in mind, ensuring all operations are GDPR compliant.
- **Multi-format Support**: Obtain profile pictures in various formats including PNG, JPG, and Base64 to facilitate easy integration with existing systems.
- **Security and Reliability**: Advanced security protocols ensure that user data is protected and responses are accurate.
- **Additional Information Retrieval**: Besides profile pictures, the service can determine WhatsApp registration status, fetch "About" info, check if a number is a WhatsApp Business account, and retrieve related business information.

## Use Cases

1. **Social Media Integration**: Integrate with social media platforms to display WhatsApp profile pictures as user avatars.
2. **Identity Verification**: Verify phone numbers for identity confirmation in services like financial platforms and e-commerce.
3. **Chat Application Enhancement**: Display profile pictures and "About" info in chat applications for enriched user interaction.
4. **Contact Management**: Validate and organize contact information with profile pictures and status messages.
5. **Messaging Automation**: Use profile pictures and registration status for personalized customer service and messaging automation.

## Tools and Endpoints

The server provides various endpoints to manage WhatsApp profile functionalities effectively, all utilizing the GET method:

- **Get Profile Picture URL**: Fetch the URL of a WhatsApp profile picture.
- **Get Profile Picture PNG**: Retrieve the profile picture as a PNG file.
- **Get Profile Picture in Base64**: Obtain the profile picture in Base64 format.
- **Get Profile Picture URI**: Access the profile picture as a URL-encoded data URI.
- **Check Profile Picture and Existence**: Verify WhatsApp registration and fetch the profile picture if available.
- **Check WhatsApp Registration**: Determine if a phone number is registered on WhatsApp.
- **Get Profile Status**: Fetch the status message of a WhatsApp profile.
- **Check WhatsApp Business Registration**: Confirm if a number is registered as a WhatsApp Business account.
- **Get Business Information**: Retrieve business information for a WhatsApp Business account.

## Error Handling

- If a user has hidden their profile picture due to privacy settings, the response will indicate this.
- If no profile picture is set, an appropriate error message will be returned.
- If a profile picture is available, the response will include the URL, Base64, URI, or JPG version of the image.

## Contact Support

For any queries or support, contact inUtil Labs Support at [info@inutil.info](mailto:info@inutil.info).