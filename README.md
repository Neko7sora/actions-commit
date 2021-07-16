# actions-commit
Composite action to commit and push changes to git using the email address of the GitHub Actions bot.

# Example
```yml
      - name: Commit to repository            
        uses: Neko7sora/actions-commit@main
        with:
          message: "[skip ci] update result.jpg and readme"
```
