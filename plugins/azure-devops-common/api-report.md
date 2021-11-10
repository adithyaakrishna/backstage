## API Report File for "@backstage/plugin-azure-devops-common"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts
// Warning: (ae-missing-release-tag) "BuildResult" is exported by the package, but it is missing a release tag (@alpha, @beta, @public, or @internal)
//
// @public (undocumented)
export enum BuildResult {
  Canceled = 32,
  Failed = 8,
  None = 0,
  PartiallySucceeded = 4,
  Succeeded = 2,
}

// Warning: (ae-missing-release-tag) "BuildStatus" is exported by the package, but it is missing a release tag (@alpha, @beta, @public, or @internal)
//
// @public (undocumented)
export enum BuildStatus {
  All = 47,
  Cancelling = 4,
  Completed = 2,
  InProgress = 1,
  None = 0,
  NotStarted = 32,
  Postponed = 8,
}

// Warning: (ae-missing-release-tag) "PullRequest" is exported by the package, but it is missing a release tag (@alpha, @beta, @public, or @internal)
//
// @public (undocumented)
export type PullRequest = {
  pullRequestId?: number;
  repoName?: string;
  title?: string;
  uniqueName?: string;
  createdBy?: string;
  creationDate?: Date;
  sourceRefName?: string;
  targetRefName?: string;
  status?: PullRequestStatus;
  isDraft?: boolean;
  link: string;
};

// Warning: (ae-missing-release-tag) "PullRequestOptions" is exported by the package, but it is missing a release tag (@alpha, @beta, @public, or @internal)
//
// @public (undocumented)
export type PullRequestOptions = {
  top: number;
  status: PullRequestStatus;
};

// Warning: (ae-missing-release-tag) "PullRequestStatus" is exported by the package, but it is missing a release tag (@alpha, @beta, @public, or @internal)
//
// @public (undocumented)
export enum PullRequestStatus {
  Abandoned = 2,
  Active = 1,
  All = 4,
  Completed = 3,
  NotSet = 0,
}

// Warning: (ae-missing-release-tag) "RepoBuild" is exported by the package, but it is missing a release tag (@alpha, @beta, @public, or @internal)
//
// @public (undocumented)
export type RepoBuild = {
  id?: number;
  title: string;
  link?: string;
  status?: BuildStatus;
  result?: BuildResult;
  queueTime?: Date;
  startTime?: Date;
  finishTime?: Date;
  source: string;
  uniqueName?: string;
};

// Warning: (ae-missing-release-tag) "RepoBuildOptions" is exported by the package, but it is missing a release tag (@alpha, @beta, @public, or @internal)
//
// @public (undocumented)
export type RepoBuildOptions = {
  top?: number;
};

// (No @packageDocumentation comment for this package)
```