# Classification of TikTok videos

## Overview

    Used statsmodels and scikit-learn to predict whether videos presented claims or opinions to improve triaging process of videos for human review.

## Business Understanding

    TikTok is working on the development of a predictive model that can determine whether a video contains a claim or offers an opinion. With a successful prediction model, TikTok can reduce the backlog of user reports and prioritize them more efficiently.

## Data Understanding

    The provided data is a Pandas DataFrame that consists of 19,382 entries, each with 12 different attributes. The first attribute is an integer column, likely serving as an index or identifier for each entry. The second attribute, ‘claim_status’, is an object column that could contain categorical data about the status of a claim, but it does have some missing values. The third attribute, ‘video_id’, is another integer column that likely represents unique identifiers for videos. The fourth attribute, ‘video_duration_sec’, is an integer column representing the duration of each video in seconds.
    The fifth attribute, ‘video_transcription_text’, is an object column that possibly contains transcriptions of the video content, but it also has some missing values. The sixth and seventh attributes, ‘verified_status’ and ‘author_ban_status’, are object columns that likely indicate whether a video or author is verified and whether the author of a video has been banned, respectively.
    The remaining five attributes are float columns representing various statistics about each video: the number of views (‘video_view_count’), likes (‘video_like_count’), shares (‘video_share_count’), downloads (‘video_download_count’), and comments (‘video_comment_count’). Each of these columns has some missing values.

## Modeling and Evaluation

    .....

## Conclusion

    .....
