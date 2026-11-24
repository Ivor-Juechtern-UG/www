# Backlog

Open work on this repository, written so a later session can pick it up. An item goes once it is done.

## 1. Photos with GPS locations, still reachable through old pull requests

Found on 24 November 2026. The history of `main` was cleaned of these photos, but GitHub keeps every pull request's commits, and anyone can still open the photos through **pull requests #1, #2 and #3** ("Files changed"). No branch reaches them any more. Both carry GPS coordinates of where they were taken:

| File | Blob |
| --- | --- |
| `main.jpeg` | `5df89a36cd` |
| `content/renewable-energy/the-grid/images/1.jpeg` | `3f4c1e2650` |

The live site is not affected: the build removes photo metadata (generator.js), and the photos on `main` carry no location.

To remove them, one of:

1. **Ask GitHub Support** to remove pull requests #1–#3 and their cached views (GitHub Docs: "Removing sensitive data from a repository", the part on pull requests and support).
2. **Recreate the repository** from the clean `main`: a new repository, `main` pushed to it, statichost.eu pointed at it, the old one deleted. Open pull requests and their discussions do not come along.

Done when a scan of every ref finds no image with GPS data:

```
git fetch origin '+refs/pull/*/head:refs/remotes/pr/*' '+refs/heads/*:refs/remotes/origin/*'
```

then read the EXIF of every .jpg, .jpeg, .png and .heic those refs reach.
