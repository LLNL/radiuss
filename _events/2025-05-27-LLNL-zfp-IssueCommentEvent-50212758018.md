---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/2238465?"
user: jwake
date: 2025-05-27
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/pull/268
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/jwake' target='_blank'>jwake</a> commented on issue <a href='https://github.com/LLNL/zfp/pull/268' target='_blank'>LLNL/zfp#268</a>.

<small>For what it's worth, I managed to get the parallel decoder working fairly well on CUDA (~70GB/sec on an A100 with buffers in device memory, though I'll note I'm only testing 3D at the moment) between this change and manually bodging the `stream_rseek` call at the end of `zfp_internal_cuda_decompress` to reset the pointer offset without trying to read from the stream (in my case, the stream was in device memory, so rseek internally trying to read the buffer would fail; short of a separate device-aware bitstream implementation I'm not sure what the best approach here would be from an API standpoint), and then manually saving/restoring the appropriate index data externally after compression / before decompression. I did note that further compressing the index data with eg. LZ4 or Deflate netted a further ~15% size improvement on the index data but with appropriate granularity the index was already pretty small compared to the bulk of the compressed data....</small>

<a href='https://github.com/LLNL/zfp/pull/268' target='_blank'>View Comment</a>