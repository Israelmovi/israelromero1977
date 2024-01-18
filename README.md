## Welcome to "Hello World" with GitHub Actionscurl --request GET \
--url "https://api.github.com/app" \
--header "Accept: application/vnd.github+json" \
--header "Authorization: Bearer YOUR_JWT" \
--header "X-GitHub-Api-Version: 2022-11-28"

This course will walk you through writing your first action and using it with a workflow file. 

**Ready to get started? Navigate to the first issue.**
curl -L \
  -H "Accept: application/vnd.github+json" \
  -H "Authorization: Bearer <YOUR-TOKEN>" \
  -H "X-GitHub-Api-Version: 2022-11-28" \
  https://api.github.com/